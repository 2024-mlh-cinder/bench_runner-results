
# Results vs. 3.10.4

- fork: python
- ref: e9b5399bee7106beeeb3
- machine: linux-x86_64
- commit hash: e9b5399
- commit date: 2023-10-19
- overall geometric mean: 1.27x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.21x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1+-e9b5399 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.67 sec: 1.19x faster                                                 |
| tornado_http   | 127 ms                                                 | 95.9 ms: 1.33x faster                                                  |
| Geometric mean | (ref)                                                  | 1.26x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1+-e9b5399 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 91.5 ms: 1.55x faster                                                  |
| float          | 111 ms                                                 | 81.7 ms: 1.35x faster                                                  |
| pidigits       | 190 ms                                                 | 195 ms: 1.03x slower                                                   |
| Geometric mean | (ref)                                                  | 1.27x faster                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1+-e9b5399 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 137 ms: 1.29x faster                                                   |
| regex_v8       | 25.0 ms                                                | 24.5 ms: 1.02x faster                                                  |
| regex_effbot   | 3.23 ms                                                | 3.63 ms: 1.12x slower                                                  |
| Geometric mean | (ref)                                                  | 1.04x faster                                                           |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1+-e9b5399 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 306 us: 1.49x faster                                                   |
| tomli_loads          | 2.92 sec                                               | 2.15 sec: 1.36x faster                                                 |
| unpickle_pure_python | 300 us                                                 | 223 us: 1.35x faster                                                   |
| json_dumps           | 13.5 ms                                                | 10.5 ms: 1.29x faster                                                  |
| xml_etree_process    | 74.9 ms                                                | 59.7 ms: 1.26x faster                                                  |
| xml_etree_generate   | 94.2 ms                                                | 86.4 ms: 1.09x faster                                                  |
| xml_etree_iterparse  | 111 ms                                                 | 106 ms: 1.05x faster                                                   |
| json_loads           | 28.8 us                                                | 27.8 us: 1.04x faster                                                  |
| xml_etree_parse      | 163 ms                                                 | 159 ms: 1.03x faster                                                   |
| unpickle_list        | 4.82 us                                                | 5.08 us: 1.05x slower                                                  |
| unpickle             | 14.1 us                                                | 15.0 us: 1.06x slower                                                  |
| pickle               | 10.3 us                                                | 11.5 us: 1.11x slower                                                  |
| pickle_list          | 4.56 us                                                | 5.14 us: 1.13x slower                                                  |
| pickle_dict          | 27.3 us                                                | 36.1 us: 1.33x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.08x faster                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1+-e9b5399 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.1 ms: 1.40x faster                                                  |
| python_startup_no_site | 5.82 ms                                                | 6.90 ms: 1.19x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.09x faster                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1+-e9b5399 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 11.7 ms: 1.26x faster                                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1+-e9b5399 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 155 us: 3.29x faster                                                   |
| generators               | 76.8 ms                                                | 29.8 ms: 2.58x faster                                                  |
| deltablue                | 7.42 ms                                                | 3.32 ms: 2.24x faster                                                  |
| asyncio_tcp              | 925 ms                                                 | 477 ms: 1.94x faster                                                   |
| chaos                    | 106 ms                                                 | 62.3 ms: 1.71x faster                                                  |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.78 sec: 1.69x faster                                                 |
| richards_super           | 90.7 ms                                                | 54.3 ms: 1.67x faster                                                  |
| raytrace                 | 464 ms                                                 | 278 ms: 1.67x faster                                                   |
| crypto_pyaes             | 118 ms                                                 | 72.2 ms: 1.64x faster                                                  |
| async_tree_none          | 717 ms                                                 | 438 ms: 1.64x faster                                                   |
| go                       | 229 ms                                                 | 143 ms: 1.60x faster                                                   |
| logging_silent           | 175 ns                                                 | 109 ns: 1.60x faster                                                   |
| sqlglot_parse            | 2.06 ms                                                | 1.29 ms: 1.60x faster                                                  |
| scimark_sor              | 197 ms                                                 | 126 ms: 1.56x faster                                                   |
| scimark_monte_carlo      | 108 ms                                                 | 69.5 ms: 1.56x faster                                                  |
| richards                 | 74.9 ms                                                | 48.4 ms: 1.55x faster                                                  |
| hexiom                   | 9.53 ms                                                | 6.15 ms: 1.55x faster                                                  |
| nbody                    | 142 ms                                                 | 91.5 ms: 1.55x faster                                                  |
| async_tree_memoization   | 854 ms                                                 | 561 ms: 1.52x faster                                                   |
| sqlglot_transpile        | 2.45 ms                                                | 1.61 ms: 1.52x faster                                                  |
| async_tree_io            | 1.77 sec                                               | 1.18 sec: 1.51x faster                                                 |
| pickle_pure_python       | 455 us                                                 | 306 us: 1.49x faster                                                   |
| pyflate                  | 673 ms                                                 | 470 ms: 1.43x faster                                                   |
| coroutines               | 31.8 ms                                                | 22.3 ms: 1.43x faster                                                  |
| scimark_lu               | 163 ms                                                 | 115 ms: 1.43x faster                                                   |
| python_startup           | 14.2 ms                                                | 10.1 ms: 1.40x faster                                                  |
| logging_simple           | 8.07 us                                                | 5.80 us: 1.39x faster                                                  |
| logging_format           | 8.91 us                                                | 6.43 us: 1.39x faster                                                  |
| tomli_loads              | 2.92 sec                                               | 2.15 sec: 1.36x faster                                                 |
| float                    | 111 ms                                                 | 81.7 ms: 1.35x faster                                                  |
| unpickle_pure_python     | 300 us                                                 | 223 us: 1.35x faster                                                   |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 716 ms: 1.33x faster                                                   |
| tornado_http             | 127 ms                                                 | 95.9 ms: 1.33x faster                                                  |
| spectral_norm            | 150 ms                                                 | 113 ms: 1.32x faster                                                   |
| deepcopy_memo            | 52.3 us                                                | 40.0 us: 1.31x faster                                                  |
| pprint_pformat           | 1.99 sec                                               | 1.52 sec: 1.31x faster                                                 |
| comprehensions           | 26.8 us                                                | 20.7 us: 1.30x faster                                                  |
| json_dumps               | 13.5 ms                                                | 10.5 ms: 1.29x faster                                                  |
| regex_compile            | 177 ms                                                 | 137 ms: 1.29x faster                                                   |
| pycparser                | 1.50 sec                                               | 1.17 sec: 1.29x faster                                                 |
| pprint_safe_repr         | 955 ms                                                 | 749 ms: 1.27x faster                                                   |
| sqlglot_normalize        | 135 ms                                                 | 107 ms: 1.27x faster                                                   |
| mako                     | 14.8 ms                                                | 11.7 ms: 1.26x faster                                                  |
| unpack_sequence          | 64.7 ns                                                | 51.3 ns: 1.26x faster                                                  |
| nqueens                  | 100 ms                                                 | 79.4 ms: 1.26x faster                                                  |
| xml_etree_process        | 74.9 ms                                                | 59.7 ms: 1.26x faster                                                  |
| mypy2                    | 428 ms                                                 | 344 ms: 1.25x faster                                                   |
| deepcopy                 | 442 us                                                 | 356 us: 1.24x faster                                                   |
| deepcopy_reduce          | 3.82 us                                                | 3.14 us: 1.22x faster                                                  |
| sqlglot_optimize         | 65.3 ms                                                | 53.7 ms: 1.22x faster                                                  |
| docutils                 | 3.17 sec                                               | 2.67 sec: 1.19x faster                                                 |
| fannkuch                 | 486 ms                                                 | 410 ms: 1.19x faster                                                   |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.63 ms: 1.18x faster                                                  |
| bench_thread_pool        | 947 us                                                 | 813 us: 1.17x faster                                                   |
| scimark_fft              | 424 ms                                                 | 365 ms: 1.16x faster                                                   |
| create_gc_cycles         | 1.67 ms                                                | 1.47 ms: 1.13x faster                                                  |
| dulwich_log              | 75.9 ms                                                | 67.4 ms: 1.13x faster                                                  |
| mdp                      | 2.82 sec                                               | 2.55 sec: 1.11x faster                                                 |
| xml_etree_generate       | 94.2 ms                                                | 86.4 ms: 1.09x faster                                                  |
| json                     | 5.42 ms                                                | 5.08 ms: 1.07x faster                                                  |
| pathlib                  | 20.0 ms                                                | 19.0 ms: 1.05x faster                                                  |
| xml_etree_iterparse      | 111 ms                                                 | 106 ms: 1.05x faster                                                   |
| meteor_contest           | 115 ms                                                 | 110 ms: 1.05x faster                                                   |
| json_loads               | 28.8 us                                                | 27.8 us: 1.04x faster                                                  |
| sqlite_synth             | 2.93 us                                                | 2.85 us: 1.03x faster                                                  |
| xml_etree_parse          | 163 ms                                                 | 159 ms: 1.03x faster                                                   |
| regex_v8                 | 25.0 ms                                                | 24.5 ms: 1.02x faster                                                  |
| gc_traversal             | 3.84 ms                                                | 3.87 ms: 1.01x slower                                                  |
| pidigits                 | 190 ms                                                 | 195 ms: 1.03x slower                                                   |
| unpickle_list            | 4.82 us                                                | 5.08 us: 1.05x slower                                                  |
| unpickle                 | 14.1 us                                                | 15.0 us: 1.06x slower                                                  |
| async_generators         | 425 ms                                                 | 452 ms: 1.06x slower                                                   |
| pickle                   | 10.3 us                                                | 11.5 us: 1.11x slower                                                  |
| regex_effbot             | 3.23 ms                                                | 3.63 ms: 1.12x slower                                                  |
| pickle_list              | 4.56 us                                                | 5.14 us: 1.13x slower                                                  |
| python_startup_no_site   | 5.82 ms                                                | 6.90 ms: 1.19x slower                                                  |
| coverage                 | 72.8 ms                                                | 90.5 ms: 1.24x slower                                                  |
| telco                    | 6.54 ms                                                | 8.39 ms: 1.28x slower                                                  |
| pickle_dict              | 27.3 us                                                | 36.1 us: 1.33x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.27x faster                                                           |

Benchmark hidden because not significant (2): regex_dna, bench_mp_pool
Ignored benchmarks (19) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.25x
- 95% likely to have a speedup of 1.25x
- 99% likely to have a speedup of 1.21x
