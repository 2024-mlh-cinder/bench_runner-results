
# Results vs. 3.10.4

- fork: brandtbucher
- ref: kwnames_tstate
- machine: linux-x86_64
- commit hash: 70d0242
- commit date: 2023-08-11
- overall geometric mean: 1.29x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.23x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.63 sec: 1.21x faster                                                |
| tornado_http   | 127 ms                                                 | 96.5 ms: 1.32x faster                                                 |
| Geometric mean | (ref)                                                  | 1.26x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 96.1 ms: 1.47x faster                                                 |
| float          | 111 ms                                                 | 81.4 ms: 1.36x faster                                                 |
| pidigits       | 190 ms                                                 | 189 ms: 1.01x faster                                                  |
| Geometric mean | (ref)                                                  | 1.26x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 137 ms: 1.29x faster                                                  |
| regex_dna      | 222 ms                                                 | 219 ms: 1.01x faster                                                  |
| regex_v8       | 25.0 ms                                                | 25.9 ms: 1.03x slower                                                 |
| regex_effbot   | 3.23 ms                                                | 3.76 ms: 1.17x slower                                                 |
| Geometric mean | (ref)                                                  | 1.02x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 303 us: 1.50x faster                                                  |
| unpickle_pure_python | 300 us                                                 | 218 us: 1.38x faster                                                  |
| json_dumps           | 13.5 ms                                                | 9.90 ms: 1.37x faster                                                 |
| tomli_loads          | 2.92 sec                                               | 2.19 sec: 1.33x faster                                                |
| xml_etree_process    | 74.9 ms                                                | 57.7 ms: 1.30x faster                                                 |
| json_loads           | 28.8 us                                                | 25.4 us: 1.13x faster                                                 |
| xml_etree_generate   | 94.2 ms                                                | 83.7 ms: 1.12x faster                                                 |
| xml_etree_iterparse  | 111 ms                                                 | 103 ms: 1.08x faster                                                  |
| xml_etree_parse      | 163 ms                                                 | 152 ms: 1.07x faster                                                  |
| unpickle             | 14.1 us                                                | 14.4 us: 1.02x slower                                                 |
| unpickle_list        | 4.82 us                                                | 4.98 us: 1.03x slower                                                 |
| pickle               | 10.3 us                                                | 10.9 us: 1.06x slower                                                 |
| pickle_dict          | 27.3 us                                                | 31.9 us: 1.17x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.13x faster                                                          |

Benchmark hidden because not significant (1): pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 9.41 ms: 1.50x faster                                                 |
| python_startup_no_site | 5.82 ms                                                | 6.88 ms: 1.18x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.13x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 11.2 ms: 1.32x faster                                                 |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242 |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 147 us: 3.46x faster                                                  |
| generators               | 76.8 ms                                                | 30.2 ms: 2.55x faster                                                 |
| deltablue                | 7.42 ms                                                | 3.32 ms: 2.24x faster                                                 |
| asyncio_tcp              | 925 ms                                                 | 499 ms: 1.85x faster                                                  |
| chaos                    | 106 ms                                                 | 60.5 ms: 1.76x faster                                                 |
| crypto_pyaes             | 118 ms                                                 | 69.5 ms: 1.70x faster                                                 |
| richards_super           | 90.7 ms                                                | 53.7 ms: 1.69x faster                                                 |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.80 sec: 1.67x faster                                                |
| raytrace                 | 464 ms                                                 | 277 ms: 1.67x faster                                                  |
| logging_silent           | 175 ns                                                 | 105 ns: 1.66x faster                                                  |
| go                       | 229 ms                                                 | 141 ms: 1.63x faster                                                  |
| async_tree_none          | 717 ms                                                 | 442 ms: 1.62x faster                                                  |
| sqlglot_parse            | 2.06 ms                                                | 1.28 ms: 1.61x faster                                                 |
| scimark_monte_carlo      | 108 ms                                                 | 67.5 ms: 1.60x faster                                                 |
| richards                 | 74.9 ms                                                | 46.7 ms: 1.60x faster                                                 |
| scimark_sor              | 197 ms                                                 | 124 ms: 1.58x faster                                                  |
| hexiom                   | 9.53 ms                                                | 6.12 ms: 1.56x faster                                                 |
| sqlglot_transpile        | 2.45 ms                                                | 1.60 ms: 1.53x faster                                                 |
| python_startup           | 14.2 ms                                                | 9.41 ms: 1.50x faster                                                 |
| pickle_pure_python       | 455 us                                                 | 303 us: 1.50x faster                                                  |
| async_tree_memoization   | 854 ms                                                 | 570 ms: 1.50x faster                                                  |
| scimark_lu               | 163 ms                                                 | 109 ms: 1.49x faster                                                  |
| async_tree_io            | 1.77 sec                                               | 1.20 sec: 1.48x faster                                                |
| nbody                    | 142 ms                                                 | 96.1 ms: 1.47x faster                                                 |
| pyflate                  | 673 ms                                                 | 458 ms: 1.47x faster                                                  |
| unpack_sequence          | 64.7 ns                                                | 45.5 ns: 1.42x faster                                                 |
| coroutines               | 31.8 ms                                                | 22.6 ms: 1.41x faster                                                 |
| deepcopy_memo            | 52.3 us                                                | 37.5 us: 1.39x faster                                                 |
| unpickle_pure_python     | 300 us                                                 | 218 us: 1.38x faster                                                  |
| json_dumps               | 13.5 ms                                                | 9.90 ms: 1.37x faster                                                 |
| spectral_norm            | 150 ms                                                 | 110 ms: 1.36x faster                                                  |
| float                    | 111 ms                                                 | 81.4 ms: 1.36x faster                                                 |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 704 ms: 1.35x faster                                                  |
| logging_simple           | 8.07 us                                                | 5.98 us: 1.35x faster                                                 |
| pprint_pformat           | 1.99 sec                                               | 1.47 sec: 1.35x faster                                                |
| logging_format           | 8.91 us                                                | 6.62 us: 1.34x faster                                                 |
| tomli_loads              | 2.92 sec                                               | 2.19 sec: 1.33x faster                                                |
| pprint_safe_repr         | 955 ms                                                 | 722 ms: 1.32x faster                                                  |
| mako                     | 14.8 ms                                                | 11.2 ms: 1.32x faster                                                 |
| tornado_http             | 127 ms                                                 | 96.5 ms: 1.32x faster                                                 |
| xml_etree_process        | 74.9 ms                                                | 57.7 ms: 1.30x faster                                                 |
| regex_compile            | 177 ms                                                 | 137 ms: 1.29x faster                                                  |
| comprehensions           | 26.8 us                                                | 20.9 us: 1.29x faster                                                 |
| sqlglot_normalize        | 135 ms                                                 | 106 ms: 1.28x faster                                                  |
| pycparser                | 1.50 sec                                               | 1.18 sec: 1.27x faster                                                |
| mypy2                    | 428 ms                                                 | 339 ms: 1.26x faster                                                  |
| deepcopy                 | 442 us                                                 | 354 us: 1.25x faster                                                  |
| nqueens                  | 100 ms                                                 | 80.5 ms: 1.24x faster                                                 |
| fannkuch                 | 486 ms                                                 | 394 ms: 1.23x faster                                                  |
| sqlglot_optimize         | 65.3 ms                                                | 53.2 ms: 1.23x faster                                                 |
| docutils                 | 3.17 sec                                               | 2.63 sec: 1.21x faster                                                |
| deepcopy_reduce          | 3.82 us                                                | 3.18 us: 1.20x faster                                                 |
| scimark_fft              | 424 ms                                                 | 363 ms: 1.17x faster                                                  |
| bench_thread_pool        | 947 us                                                 | 822 us: 1.15x faster                                                  |
| dulwich_log              | 75.9 ms                                                | 66.9 ms: 1.14x faster                                                 |
| json_loads               | 28.8 us                                                | 25.4 us: 1.13x faster                                                 |
| xml_etree_generate       | 94.2 ms                                                | 83.7 ms: 1.12x faster                                                 |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.88 ms: 1.12x faster                                                 |
| json                     | 5.42 ms                                                | 4.89 ms: 1.11x faster                                                 |
| create_gc_cycles         | 1.67 ms                                                | 1.51 ms: 1.11x faster                                                 |
| mdp                      | 2.82 sec                                               | 2.59 sec: 1.09x faster                                                |
| sqlite_synth             | 2.93 us                                                | 2.71 us: 1.08x faster                                                 |
| meteor_contest           | 115 ms                                                 | 106 ms: 1.08x faster                                                  |
| xml_etree_iterparse      | 111 ms                                                 | 103 ms: 1.08x faster                                                  |
| pathlib                  | 20.0 ms                                                | 18.6 ms: 1.08x faster                                                 |
| xml_etree_parse          | 163 ms                                                 | 152 ms: 1.07x faster                                                  |
| regex_dna                | 222 ms                                                 | 219 ms: 1.01x faster                                                  |
| pidigits                 | 190 ms                                                 | 189 ms: 1.01x faster                                                  |
| unpickle                 | 14.1 us                                                | 14.4 us: 1.02x slower                                                 |
| unpickle_list            | 4.82 us                                                | 4.98 us: 1.03x slower                                                 |
| regex_v8                 | 25.0 ms                                                | 25.9 ms: 1.03x slower                                                 |
| pickle                   | 10.3 us                                                | 10.9 us: 1.06x slower                                                 |
| async_generators         | 425 ms                                                 | 453 ms: 1.06x slower                                                  |
| gc_traversal             | 3.84 ms                                                | 4.25 ms: 1.11x slower                                                 |
| regex_effbot             | 3.23 ms                                                | 3.76 ms: 1.17x slower                                                 |
| pickle_dict              | 27.3 us                                                | 31.9 us: 1.17x slower                                                 |
| coverage                 | 72.8 ms                                                | 85.7 ms: 1.18x slower                                                 |
| python_startup_no_site   | 5.82 ms                                                | 6.88 ms: 1.18x slower                                                 |
| telco                    | 6.54 ms                                                | 8.15 ms: 1.25x slower                                                 |
| dask                     | 423 ms                                                 | 526 ms: 1.25x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.29x faster                                                          |

Benchmark hidden because not significant (2): pickle_list, bench_mp_pool
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.26x
- 95% likely to have a speedup of 1.25x
- 99% likely to have a speedup of 1.23x
