
# Results vs. 3.10.4

- fork: python
- ref: v3.11.5
- machine: linux-x86_64
- commit hash: cce6ba9
- commit date: 2023-08-24
- overall geometric mean: 1.25x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.19x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230824-linux-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 336 ms                                                 | 259 ms: 1.30x faster                                   |
| chameleon      | 9.06 ms                                                | 6.61 ms: 1.37x faster                                  |
| docutils       | 3.17 sec                                               | 2.59 sec: 1.22x faster                                 |
| html5lib       | 85.9 ms                                                | 64.2 ms: 1.34x faster                                  |
| tornado_http   | 127 ms                                                 | 96.7 ms: 1.32x faster                                  |
| Geometric mean | (ref)                                                  | 1.31x faster                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230824-linux-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| nbody          | 142 ms                                                 | 95.6 ms: 1.48x faster                                  |
| float          | 111 ms                                                 | 77.0 ms: 1.43x faster                                  |
| Geometric mean | (ref)                                                  | 1.29x faster                                           |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230824-linux-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 136 ms: 1.30x faster                                   |
| regex_v8       | 25.0 ms                                                | 21.8 ms: 1.15x faster                                  |
| regex_dna      | 222 ms                                                 | 201 ms: 1.10x faster                                   |
| regex_effbot   | 3.23 ms                                                | 3.25 ms: 1.01x slower                                  |
| Geometric mean | (ref)                                                  | 1.13x faster                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230824-linux-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 306 us: 1.49x faster                                   |
| xml_etree_process    | 74.9 ms                                                | 53.8 ms: 1.39x faster                                  |
| unpickle_pure_python | 300 us                                                 | 229 us: 1.31x faster                                   |
| tomli_loads          | 2.92 sec                                               | 2.22 sec: 1.31x faster                                 |
| xml_etree_generate   | 94.2 ms                                                | 76.2 ms: 1.24x faster                                  |
| json_loads           | 28.8 us                                                | 25.9 us: 1.11x faster                                  |
| pickle_list          | 4.56 us                                                | 4.12 us: 1.11x faster                                  |
| json_dumps           | 13.5 ms                                                | 12.6 ms: 1.07x faster                                  |
| unpickle             | 14.1 us                                                | 13.3 us: 1.06x faster                                  |
| xml_etree_iterparse  | 111 ms                                                 | 105 ms: 1.06x faster                                   |
| xml_etree_parse      | 163 ms                                                 | 159 ms: 1.03x faster                                   |
| pickle               | 10.3 us                                                | 10.0 us: 1.03x faster                                  |
| unpickle_list        | 4.82 us                                                | 5.00 us: 1.04x slower                                  |
| pickle_dict          | 27.3 us                                                | 31.0 us: 1.14x slower                                  |
| Geometric mean       | (ref)                                                  | 1.13x faster                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230824-linux-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 8.56 ms: 1.65x faster                                  |
| python_startup_no_site | 5.82 ms                                                | 6.04 ms: 1.04x slower                                  |
| Geometric mean         | (ref)                                                  | 1.26x faster                                           |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230824-linux-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|-----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako            | 14.8 ms                                                | 9.99 ms: 1.48x faster                                  |
| django_template | 45.9 ms                                                | 32.6 ms: 1.41x faster                                  |
| genshi_text     | 30.3 ms                                                | 22.3 ms: 1.36x faster                                  |
| genshi_xml      | 63.3 ms                                                | 52.8 ms: 1.20x faster                                  |
| Geometric mean  | (ref)                                                  | 1.36x faster                                           |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230824-linux-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| deltablue                | 7.42 ms                                                | 3.69 ms: 2.01x faster                                  |
| logging_silent           | 175 ns                                                 | 98.6 ns: 1.78x faster                                  |
| scimark_sor              | 197 ms                                                 | 117 ms: 1.68x faster                                   |
| python_startup           | 14.2 ms                                                | 8.56 ms: 1.65x faster                                  |
| go                       | 229 ms                                                 | 141 ms: 1.63x faster                                   |
| pyflate                  | 673 ms                                                 | 419 ms: 1.61x faster                                   |
| crypto_pyaes             | 118 ms                                                 | 73.9 ms: 1.60x faster                                  |
| richards                 | 74.9 ms                                                | 47.1 ms: 1.59x faster                                  |
| scimark_monte_carlo      | 108 ms                                                 | 68.8 ms: 1.57x faster                                  |
| raytrace                 | 464 ms                                                 | 295 ms: 1.57x faster                                   |
| richards_super           | 90.7 ms                                                | 58.3 ms: 1.56x faster                                  |
| chaos                    | 106 ms                                                 | 68.5 ms: 1.55x faster                                  |
| scimark_lu               | 163 ms                                                 | 107 ms: 1.52x faster                                   |
| sqlglot_parse            | 2.06 ms                                                | 1.37 ms: 1.50x faster                                  |
| hexiom                   | 9.53 ms                                                | 6.39 ms: 1.49x faster                                  |
| pickle_pure_python       | 455 us                                                 | 306 us: 1.49x faster                                   |
| nbody                    | 142 ms                                                 | 95.6 ms: 1.48x faster                                  |
| mako                     | 14.8 ms                                                | 9.99 ms: 1.48x faster                                  |
| unpack_sequence          | 64.7 ns                                                | 43.9 ns: 1.47x faster                                  |
| sqlglot_transpile        | 2.45 ms                                                | 1.67 ms: 1.46x faster                                  |
| spectral_norm            | 150 ms                                                 | 104 ms: 1.44x faster                                   |
| float                    | 111 ms                                                 | 77.0 ms: 1.43x faster                                  |
| django_template          | 45.9 ms                                                | 32.6 ms: 1.41x faster                                  |
| deepcopy_memo            | 52.3 us                                                | 37.2 us: 1.41x faster                                  |
| xml_etree_process        | 74.9 ms                                                | 53.8 ms: 1.39x faster                                  |
| chameleon                | 9.06 ms                                                | 6.61 ms: 1.37x faster                                  |
| pprint_pformat           | 1.99 sec                                               | 1.45 sec: 1.37x faster                                 |
| pprint_safe_repr         | 955 ms                                                 | 700 ms: 1.36x faster                                   |
| async_tree_none          | 717 ms                                                 | 526 ms: 1.36x faster                                   |
| genshi_text              | 30.3 ms                                                | 22.3 ms: 1.36x faster                                  |
| async_tree_io            | 1.77 sec                                               | 1.30 sec: 1.36x faster                                 |
| logging_simple           | 8.07 us                                                | 5.93 us: 1.36x faster                                  |
| logging_format           | 8.91 us                                                | 6.55 us: 1.36x faster                                  |
| thrift                   | 1.03 ms                                                | 763 us: 1.35x faster                                   |
| html5lib                 | 85.9 ms                                                | 64.2 ms: 1.34x faster                                  |
| async_tree_memoization   | 854 ms                                                 | 641 ms: 1.33x faster                                   |
| pycparser                | 1.50 sec                                               | 1.13 sec: 1.32x faster                                 |
| tornado_http             | 127 ms                                                 | 96.7 ms: 1.32x faster                                  |
| unpickle_pure_python     | 300 us                                                 | 229 us: 1.31x faster                                   |
| tomli_loads              | 2.92 sec                                               | 2.22 sec: 1.31x faster                                 |
| 2to3                     | 336 ms                                                 | 259 ms: 1.30x faster                                   |
| regex_compile            | 177 ms                                                 | 136 ms: 1.30x faster                                   |
| scimark_fft              | 424 ms                                                 | 329 ms: 1.29x faster                                   |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 740 ms: 1.29x faster                                   |
| deepcopy_reduce          | 3.82 us                                                | 2.99 us: 1.28x faster                                  |
| fannkuch                 | 486 ms                                                 | 383 ms: 1.27x faster                                   |
| deepcopy                 | 442 us                                                 | 351 us: 1.26x faster                                   |
| aiohttp                  | 1.38 ms                                                | 1.10 ms: 1.25x faster                                  |
| coroutines               | 31.8 ms                                                | 25.4 ms: 1.25x faster                                  |
| sqlglot_normalize        | 135 ms                                                 | 108 ms: 1.25x faster                                   |
| xml_etree_generate       | 94.2 ms                                                | 76.2 ms: 1.24x faster                                  |
| sqlglot_optimize         | 65.3 ms                                                | 53.0 ms: 1.23x faster                                  |
| gunicorn                 | 1.46 ms                                                | 1.19 ms: 1.22x faster                                  |
| docutils                 | 3.17 sec                                               | 2.59 sec: 1.22x faster                                 |
| genshi_xml               | 63.3 ms                                                | 52.8 ms: 1.20x faster                                  |
| dulwich_log              | 75.9 ms                                                | 63.8 ms: 1.19x faster                                  |
| nqueens                  | 100 ms                                                 | 84.2 ms: 1.19x faster                                  |
| sqlalchemy_imperative    | 21.2 ms                                                | 17.9 ms: 1.19x faster                                  |
| comprehensions           | 26.8 us                                                | 22.7 us: 1.18x faster                                  |
| sqlalchemy_declarative   | 165 ms                                                 | 140 ms: 1.18x faster                                   |
| async_generators         | 425 ms                                                 | 361 ms: 1.18x faster                                   |
| dask                     | 423 ms                                                 | 360 ms: 1.17x faster                                   |
| sqlite_synth             | 2.93 us                                                | 2.52 us: 1.16x faster                                  |
| bench_thread_pool        | 947 us                                                 | 818 us: 1.16x faster                                   |
| flaskblogging            | 8.27 ms                                                | 7.14 ms: 1.16x faster                                  |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.72 ms: 1.16x faster                                  |
| sympy_integrate          | 24.3 ms                                                | 21.1 ms: 1.15x faster                                  |
| regex_v8                 | 25.0 ms                                                | 21.8 ms: 1.15x faster                                  |
| pylint                   | 525 ms                                                 | 458 ms: 1.15x faster                                   |
| sympy_expand             | 545 ms                                                 | 476 ms: 1.14x faster                                   |
| sympy_str                | 328 ms                                                 | 291 ms: 1.13x faster                                   |
| create_gc_cycles         | 1.67 ms                                                | 1.48 ms: 1.13x faster                                  |
| json                     | 5.42 ms                                                | 4.83 ms: 1.12x faster                                  |
| json_loads               | 28.8 us                                                | 25.9 us: 1.11x faster                                  |
| pathlib                  | 20.0 ms                                                | 18.1 ms: 1.11x faster                                  |
| pickle_list              | 4.56 us                                                | 4.12 us: 1.11x faster                                  |
| regex_dna                | 222 ms                                                 | 201 ms: 1.10x faster                                   |
| sympy_sum                | 185 ms                                                 | 167 ms: 1.10x faster                                   |
| meteor_contest           | 115 ms                                                 | 105 ms: 1.09x faster                                   |
| djangocms                | 35.9 us                                                | 32.9 us: 1.09x faster                                  |
| mdp                      | 2.82 sec                                               | 2.59 sec: 1.09x faster                                 |
| json_dumps               | 13.5 ms                                                | 12.6 ms: 1.07x faster                                  |
| asyncio_tcp              | 925 ms                                                 | 864 ms: 1.07x faster                                   |
| unpickle                 | 14.1 us                                                | 13.3 us: 1.06x faster                                  |
| xml_etree_iterparse      | 111 ms                                                 | 105 ms: 1.06x faster                                   |
| gc_traversal             | 3.84 ms                                                | 3.64 ms: 1.06x faster                                  |
| generators               | 76.8 ms                                                | 73.8 ms: 1.04x faster                                  |
| typing_runtime_protocols | 510 us                                                 | 493 us: 1.03x faster                                   |
| xml_etree_parse          | 163 ms                                                 | 159 ms: 1.03x faster                                   |
| pickle                   | 10.3 us                                                | 10.0 us: 1.03x faster                                  |
| regex_effbot             | 3.23 ms                                                | 3.25 ms: 1.01x slower                                  |
| telco                    | 6.54 ms                                                | 6.60 ms: 1.01x slower                                  |
| python_startup_no_site   | 5.82 ms                                                | 6.04 ms: 1.04x slower                                  |
| unpickle_list            | 4.82 us                                                | 5.00 us: 1.04x slower                                  |
| asyncio_tcp_ssl          | 3.01 sec                                               | 3.18 sec: 1.06x slower                                 |
| pickle_dict              | 27.3 us                                                | 31.0 us: 1.14x slower                                  |
| mypy2                    | 428 ms                                                 | 532 ms: 1.24x slower                                   |
| Geometric mean           | (ref)                                                  | 1.25x faster                                           |

Benchmark hidden because not significant (2): pidigits, bench_mp_pool
Ignored benchmarks (1) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: coverage


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.22x
- 95% likely to have a speedup of 1.21x
- 99% likely to have a speedup of 1.19x
