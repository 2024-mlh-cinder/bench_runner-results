
# Results vs. 3.10.4

- fork: python
- ref: v3.11.6
- machine: linux-x86_64
- commit hash: 8b6ee5b
- commit date: 2023-10-02
- overall geometric mean: 1.25x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.19x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-linux-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 336 ms                                                 | 257 ms: 1.31x faster                                   |
| chameleon      | 9.06 ms                                                | 6.61 ms: 1.37x faster                                  |
| docutils       | 3.17 sec                                               | 2.58 sec: 1.23x faster                                 |
| html5lib       | 85.9 ms                                                | 63.9 ms: 1.34x faster                                  |
| tornado_http   | 127 ms                                                 | 96.9 ms: 1.31x faster                                  |
| Geometric mean | (ref)                                                  | 1.31x faster                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-linux-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| nbody          | 142 ms                                                 | 92.6 ms: 1.53x faster                                  |
| float          | 111 ms                                                 | 75.7 ms: 1.46x faster                                  |
| pidigits       | 190 ms                                                 | 199 ms: 1.05x slower                                   |
| Geometric mean | (ref)                                                  | 1.29x faster                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-linux-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 136 ms: 1.30x faster                                   |
| regex_v8       | 25.0 ms                                                | 21.9 ms: 1.14x faster                                  |
| regex_dna      | 222 ms                                                 | 199 ms: 1.12x faster                                   |
| regex_effbot   | 3.23 ms                                                | 3.47 ms: 1.08x slower                                  |
| Geometric mean | (ref)                                                  | 1.11x faster                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-linux-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 306 us: 1.49x faster                                   |
| xml_etree_process    | 74.9 ms                                                | 53.7 ms: 1.39x faster                                  |
| unpickle_pure_python | 300 us                                                 | 230 us: 1.31x faster                                   |
| tomli_loads          | 2.92 sec                                               | 2.25 sec: 1.30x faster                                 |
| xml_etree_generate   | 94.2 ms                                                | 76.7 ms: 1.23x faster                                  |
| json_loads           | 28.8 us                                                | 23.9 us: 1.21x faster                                  |
| pickle_list          | 4.56 us                                                | 4.05 us: 1.12x faster                                  |
| xml_etree_iterparse  | 111 ms                                                 | 103 ms: 1.08x faster                                   |
| json_dumps           | 13.5 ms                                                | 12.7 ms: 1.07x faster                                  |
| unpickle             | 14.1 us                                                | 13.3 us: 1.06x faster                                  |
| pickle               | 10.3 us                                                | 9.82 us: 1.05x faster                                  |
| xml_etree_parse      | 163 ms                                                 | 158 ms: 1.03x faster                                   |
| unpickle_list        | 4.82 us                                                | 5.08 us: 1.05x slower                                  |
| pickle_dict          | 27.3 us                                                | 29.9 us: 1.10x slower                                  |
| Geometric mean       | (ref)                                                  | 1.15x faster                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-linux-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 8.50 ms: 1.67x faster                                  |
| python_startup_no_site | 5.82 ms                                                | 6.00 ms: 1.03x slower                                  |
| Geometric mean         | (ref)                                                  | 1.27x faster                                           |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-linux-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|-----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako            | 14.8 ms                                                | 9.88 ms: 1.49x faster                                  |
| django_template | 45.9 ms                                                | 33.1 ms: 1.39x faster                                  |
| genshi_text     | 30.3 ms                                                | 21.9 ms: 1.38x faster                                  |
| genshi_xml      | 63.3 ms                                                | 51.5 ms: 1.23x faster                                  |
| Geometric mean  | (ref)                                                  | 1.37x faster                                           |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-linux-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| deltablue                | 7.42 ms                                                | 3.94 ms: 1.89x faster                                  |
| logging_silent           | 175 ns                                                 | 101 ns: 1.73x faster                                   |
| scimark_sor              | 197 ms                                                 | 118 ms: 1.67x faster                                   |
| python_startup           | 14.2 ms                                                | 8.50 ms: 1.67x faster                                  |
| go                       | 229 ms                                                 | 140 ms: 1.64x faster                                   |
| pyflate                  | 673 ms                                                 | 412 ms: 1.63x faster                                   |
| crypto_pyaes             | 118 ms                                                 | 74.4 ms: 1.59x faster                                  |
| raytrace                 | 464 ms                                                 | 293 ms: 1.58x faster                                   |
| scimark_monte_carlo      | 108 ms                                                 | 68.5 ms: 1.58x faster                                  |
| richards                 | 74.9 ms                                                | 47.9 ms: 1.56x faster                                  |
| chaos                    | 106 ms                                                 | 68.8 ms: 1.54x faster                                  |
| richards_super           | 90.7 ms                                                | 59.0 ms: 1.54x faster                                  |
| nbody                    | 142 ms                                                 | 92.6 ms: 1.53x faster                                  |
| unpack_sequence          | 64.7 ns                                                | 42.9 ns: 1.51x faster                                  |
| sqlglot_parse            | 2.06 ms                                                | 1.37 ms: 1.50x faster                                  |
| mako                     | 14.8 ms                                                | 9.88 ms: 1.49x faster                                  |
| scimark_lu               | 163 ms                                                 | 110 ms: 1.49x faster                                   |
| pickle_pure_python       | 455 us                                                 | 306 us: 1.49x faster                                   |
| hexiom                   | 9.53 ms                                                | 6.49 ms: 1.47x faster                                  |
| float                    | 111 ms                                                 | 75.7 ms: 1.46x faster                                  |
| sqlglot_transpile        | 2.45 ms                                                | 1.68 ms: 1.46x faster                                  |
| spectral_norm            | 150 ms                                                 | 103 ms: 1.45x faster                                   |
| deepcopy_memo            | 52.3 us                                                | 36.3 us: 1.44x faster                                  |
| xml_etree_process        | 74.9 ms                                                | 53.7 ms: 1.39x faster                                  |
| django_template          | 45.9 ms                                                | 33.1 ms: 1.39x faster                                  |
| genshi_text              | 30.3 ms                                                | 21.9 ms: 1.38x faster                                  |
| async_tree_none          | 717 ms                                                 | 522 ms: 1.37x faster                                   |
| chameleon                | 9.06 ms                                                | 6.61 ms: 1.37x faster                                  |
| pprint_pformat           | 1.99 sec                                               | 1.45 sec: 1.37x faster                                 |
| logging_format           | 8.91 us                                                | 6.52 us: 1.37x faster                                  |
| thrift                   | 1.03 ms                                                | 757 us: 1.37x faster                                   |
| async_tree_io            | 1.77 sec                                               | 1.30 sec: 1.36x faster                                 |
| logging_simple           | 8.07 us                                                | 5.93 us: 1.36x faster                                  |
| pprint_safe_repr         | 955 ms                                                 | 703 ms: 1.36x faster                                   |
| async_tree_memoization   | 854 ms                                                 | 632 ms: 1.35x faster                                   |
| pycparser                | 1.50 sec                                               | 1.12 sec: 1.35x faster                                 |
| html5lib                 | 85.9 ms                                                | 63.9 ms: 1.34x faster                                  |
| tornado_http             | 127 ms                                                 | 96.9 ms: 1.31x faster                                  |
| 2to3                     | 336 ms                                                 | 257 ms: 1.31x faster                                   |
| unpickle_pure_python     | 300 us                                                 | 230 us: 1.31x faster                                   |
| regex_compile            | 177 ms                                                 | 136 ms: 1.30x faster                                   |
| tomli_loads              | 2.92 sec                                               | 2.25 sec: 1.30x faster                                 |
| deepcopy                 | 442 us                                                 | 342 us: 1.29x faster                                   |
| deepcopy_reduce          | 3.82 us                                                | 2.98 us: 1.28x faster                                  |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 742 ms: 1.28x faster                                   |
| scimark_fft              | 424 ms                                                 | 332 ms: 1.28x faster                                   |
| aiohttp                  | 1.38 ms                                                | 1.10 ms: 1.26x faster                                  |
| fannkuch                 | 486 ms                                                 | 387 ms: 1.26x faster                                   |
| sqlglot_normalize        | 135 ms                                                 | 108 ms: 1.25x faster                                   |
| gunicorn                 | 1.46 ms                                                | 1.17 ms: 1.24x faster                                  |
| sqlglot_optimize         | 65.3 ms                                                | 53.0 ms: 1.23x faster                                  |
| docutils                 | 3.17 sec                                               | 2.58 sec: 1.23x faster                                 |
| xml_etree_generate       | 94.2 ms                                                | 76.7 ms: 1.23x faster                                  |
| genshi_xml               | 63.3 ms                                                | 51.5 ms: 1.23x faster                                  |
| coroutines               | 31.8 ms                                                | 25.9 ms: 1.23x faster                                  |
| comprehensions           | 26.8 us                                                | 22.2 us: 1.21x faster                                  |
| json_loads               | 28.8 us                                                | 23.9 us: 1.21x faster                                  |
| sqlalchemy_imperative    | 21.2 ms                                                | 17.7 ms: 1.20x faster                                  |
| async_generators         | 425 ms                                                 | 356 ms: 1.20x faster                                   |
| nqueens                  | 100 ms                                                 | 83.7 ms: 1.19x faster                                  |
| sqlalchemy_declarative   | 165 ms                                                 | 139 ms: 1.19x faster                                   |
| json                     | 5.42 ms                                                | 4.59 ms: 1.18x faster                                  |
| dask                     | 423 ms                                                 | 358 ms: 1.18x faster                                   |
| dulwich_log              | 75.9 ms                                                | 64.5 ms: 1.18x faster                                  |
| flaskblogging            | 8.27 ms                                                | 7.04 ms: 1.17x faster                                  |
| sqlite_synth             | 2.93 us                                                | 2.50 us: 1.17x faster                                  |
| sympy_integrate          | 24.3 ms                                                | 20.8 ms: 1.17x faster                                  |
| sympy_expand             | 545 ms                                                 | 471 ms: 1.16x faster                                   |
| bench_thread_pool        | 947 us                                                 | 821 us: 1.15x faster                                   |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.76 ms: 1.15x faster                                  |
| sympy_str                | 328 ms                                                 | 287 ms: 1.14x faster                                   |
| regex_v8                 | 25.0 ms                                                | 21.9 ms: 1.14x faster                                  |
| create_gc_cycles         | 1.67 ms                                                | 1.47 ms: 1.13x faster                                  |
| pickle_list              | 4.56 us                                                | 4.05 us: 1.12x faster                                  |
| regex_dna                | 222 ms                                                 | 199 ms: 1.12x faster                                   |
| sympy_sum                | 185 ms                                                 | 165 ms: 1.12x faster                                   |
| pylint                   | 525 ms                                                 | 473 ms: 1.11x faster                                   |
| djangocms                | 35.9 us                                                | 32.6 us: 1.10x faster                                  |
| pathlib                  | 20.0 ms                                                | 18.2 ms: 1.10x faster                                  |
| meteor_contest           | 115 ms                                                 | 105 ms: 1.09x faster                                   |
| xml_etree_iterparse      | 111 ms                                                 | 103 ms: 1.08x faster                                   |
| json_dumps               | 13.5 ms                                                | 12.7 ms: 1.07x faster                                  |
| generators               | 76.8 ms                                                | 72.2 ms: 1.06x faster                                  |
| unpickle                 | 14.1 us                                                | 13.3 us: 1.06x faster                                  |
| pickle                   | 10.3 us                                                | 9.82 us: 1.05x faster                                  |
| typing_runtime_protocols | 510 us                                                 | 493 us: 1.03x faster                                   |
| xml_etree_parse          | 163 ms                                                 | 158 ms: 1.03x faster                                   |
| mdp                      | 2.82 sec                                               | 2.81 sec: 1.00x faster                                 |
| asyncio_tcp              | 925 ms                                                 | 934 ms: 1.01x slower                                   |
| telco                    | 6.54 ms                                                | 6.66 ms: 1.02x slower                                  |
| python_startup_no_site   | 5.82 ms                                                | 6.00 ms: 1.03x slower                                  |
| asyncio_tcp_ssl          | 3.01 sec                                               | 3.14 sec: 1.05x slower                                 |
| pidigits                 | 190 ms                                                 | 199 ms: 1.05x slower                                   |
| unpickle_list            | 4.82 us                                                | 5.08 us: 1.05x slower                                  |
| regex_effbot             | 3.23 ms                                                | 3.47 ms: 1.08x slower                                  |
| pickle_dict              | 27.3 us                                                | 29.9 us: 1.10x slower                                  |
| gc_traversal             | 3.84 ms                                                | 4.25 ms: 1.11x slower                                  |
| mypy2                    | 428 ms                                                 | 529 ms: 1.23x slower                                   |
| Geometric mean           | (ref)                                                  | 1.25x faster                                           |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (1) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: coverage


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.23x
- 95% likely to have a speedup of 1.22x
- 99% likely to have a speedup of 1.19x
