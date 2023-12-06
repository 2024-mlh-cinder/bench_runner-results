
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_opargs
- machine: linux-x86_64
- commit hash: 9d7c25a
- commit date: 2023-09-06
- overall geometric mean: 1.26x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.17x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.71 sec: 1.17x faster                                               |
| tornado_http   | 127 ms                                                 | 97.9 ms: 1.30x faster                                                |
| Geometric mean | (ref)                                                  | 1.23x faster                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 99.8 ms: 1.42x faster                                                |
| float          | 111 ms                                                 | 83.3 ms: 1.33x faster                                                |
| pidigits       | 190 ms                                                 | 187 ms: 1.01x faster                                                 |
| Geometric mean | (ref)                                                  | 1.24x faster                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 147 ms: 1.20x faster                                                 |
| regex_dna      | 222 ms                                                 | 222 ms: 1.00x slower                                                 |
| regex_v8       | 25.0 ms                                                | 25.4 ms: 1.01x slower                                                |
| regex_effbot   | 3.23 ms                                                | 3.63 ms: 1.12x slower                                                |
| Geometric mean | (ref)                                                  | 1.01x faster                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 306 us: 1.49x faster                                                 |
| json_dumps           | 13.5 ms                                                | 9.96 ms: 1.36x faster                                                |
| tomli_loads          | 2.92 sec                                               | 2.22 sec: 1.32x faster                                               |
| unpickle_pure_python | 300 us                                                 | 228 us: 1.31x faster                                                 |
| xml_etree_process    | 74.9 ms                                                | 58.3 ms: 1.29x faster                                                |
| json_loads           | 28.8 us                                                | 25.0 us: 1.15x faster                                                |
| xml_etree_generate   | 94.2 ms                                                | 83.3 ms: 1.13x faster                                                |
| xml_etree_parse      | 163 ms                                                 | 152 ms: 1.08x faster                                                 |
| xml_etree_iterparse  | 111 ms                                                 | 104 ms: 1.07x faster                                                 |
| unpickle             | 14.1 us                                                | 13.9 us: 1.02x faster                                                |
| pickle_list          | 4.56 us                                                | 4.62 us: 1.01x slower                                                |
| unpickle_list        | 4.82 us                                                | 4.99 us: 1.03x slower                                                |
| pickle               | 10.3 us                                                | 10.7 us: 1.04x slower                                                |
| pickle_dict          | 27.3 us                                                | 31.7 us: 1.16x slower                                                |
| Geometric mean       | (ref)                                                  | 1.13x faster                                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 9.84 ms: 1.44x faster                                                |
| python_startup_no_site | 5.82 ms                                                | 7.32 ms: 1.26x slower                                                |
| Geometric mean         | (ref)                                                  | 1.07x faster                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 11.7 ms: 1.26x faster                                                |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 153 us: 3.33x faster                                                 |
| generators               | 76.8 ms                                                | 29.8 ms: 2.58x faster                                                |
| deltablue                | 7.42 ms                                                | 3.46 ms: 2.15x faster                                                |
| asyncio_tcp              | 925 ms                                                 | 491 ms: 1.88x faster                                                 |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.80 sec: 1.67x faster                                               |
| logging_silent           | 175 ns                                                 | 105 ns: 1.66x faster                                                 |
| richards_super           | 90.7 ms                                                | 54.7 ms: 1.66x faster                                                |
| raytrace                 | 464 ms                                                 | 282 ms: 1.65x faster                                                 |
| crypto_pyaes             | 118 ms                                                 | 72.0 ms: 1.65x faster                                                |
| chaos                    | 106 ms                                                 | 65.4 ms: 1.63x faster                                                |
| async_tree_none          | 717 ms                                                 | 445 ms: 1.61x faster                                                 |
| scimark_sor              | 197 ms                                                 | 123 ms: 1.60x faster                                                 |
| sqlglot_parse            | 2.06 ms                                                | 1.30 ms: 1.59x faster                                                |
| scimark_monte_carlo      | 108 ms                                                 | 68.8 ms: 1.57x faster                                                |
| go                       | 229 ms                                                 | 148 ms: 1.55x faster                                                 |
| richards                 | 74.9 ms                                                | 48.5 ms: 1.54x faster                                                |
| sqlglot_transpile        | 2.45 ms                                                | 1.62 ms: 1.51x faster                                                |
| pickle_pure_python       | 455 us                                                 | 306 us: 1.49x faster                                                 |
| async_tree_memoization   | 854 ms                                                 | 578 ms: 1.48x faster                                                 |
| async_tree_io            | 1.77 sec                                               | 1.21 sec: 1.47x faster                                               |
| coroutines               | 31.8 ms                                                | 22.1 ms: 1.44x faster                                                |
| python_startup           | 14.2 ms                                                | 9.84 ms: 1.44x faster                                                |
| scimark_lu               | 163 ms                                                 | 114 ms: 1.43x faster                                                 |
| nbody                    | 142 ms                                                 | 99.8 ms: 1.42x faster                                                |
| pyflate                  | 673 ms                                                 | 479 ms: 1.41x faster                                                 |
| unpack_sequence          | 64.7 ns                                                | 46.9 ns: 1.38x faster                                                |
| logging_simple           | 8.07 us                                                | 5.91 us: 1.36x faster                                                |
| logging_format           | 8.91 us                                                | 6.53 us: 1.36x faster                                                |
| json_dumps               | 13.5 ms                                                | 9.96 ms: 1.36x faster                                                |
| deepcopy_memo            | 52.3 us                                                | 38.6 us: 1.36x faster                                                |
| hexiom                   | 9.53 ms                                                | 7.13 ms: 1.34x faster                                                |
| spectral_norm            | 150 ms                                                 | 113 ms: 1.33x faster                                                 |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 714 ms: 1.33x faster                                                 |
| float                    | 111 ms                                                 | 83.3 ms: 1.33x faster                                                |
| tomli_loads              | 2.92 sec                                               | 2.22 sec: 1.32x faster                                               |
| unpickle_pure_python     | 300 us                                                 | 228 us: 1.31x faster                                                 |
| tornado_http             | 127 ms                                                 | 97.9 ms: 1.30x faster                                                |
| pprint_pformat           | 1.99 sec                                               | 1.54 sec: 1.29x faster                                               |
| xml_etree_process        | 74.9 ms                                                | 58.3 ms: 1.29x faster                                                |
| pprint_safe_repr         | 955 ms                                                 | 748 ms: 1.28x faster                                                 |
| sqlglot_normalize        | 135 ms                                                 | 107 ms: 1.27x faster                                                 |
| mako                     | 14.8 ms                                                | 11.7 ms: 1.26x faster                                                |
| deepcopy                 | 442 us                                                 | 358 us: 1.24x faster                                                 |
| deepcopy_reduce          | 3.82 us                                                | 3.10 us: 1.23x faster                                                |
| pycparser                | 1.50 sec                                               | 1.22 sec: 1.23x faster                                               |
| mypy2                    | 428 ms                                                 | 355 ms: 1.21x faster                                                 |
| sqlglot_optimize         | 65.3 ms                                                | 54.1 ms: 1.21x faster                                                |
| regex_compile            | 177 ms                                                 | 147 ms: 1.20x faster                                                 |
| docutils                 | 3.17 sec                                               | 2.71 sec: 1.17x faster                                               |
| json_loads               | 28.8 us                                                | 25.0 us: 1.15x faster                                                |
| scimark_fft              | 424 ms                                                 | 373 ms: 1.14x faster                                                 |
| xml_etree_generate       | 94.2 ms                                                | 83.3 ms: 1.13x faster                                                |
| fannkuch                 | 486 ms                                                 | 430 ms: 1.13x faster                                                 |
| bench_thread_pool        | 947 us                                                 | 839 us: 1.13x faster                                                 |
| comprehensions           | 26.8 us                                                | 23.9 us: 1.12x faster                                                |
| json                     | 5.42 ms                                                | 4.86 ms: 1.11x faster                                                |
| create_gc_cycles         | 1.67 ms                                                | 1.50 ms: 1.11x faster                                                |
| dulwich_log              | 75.9 ms                                                | 68.7 ms: 1.11x faster                                                |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 5.05 ms: 1.08x faster                                                |
| xml_etree_parse          | 163 ms                                                 | 152 ms: 1.08x faster                                                 |
| mdp                      | 2.82 sec                                               | 2.63 sec: 1.07x faster                                               |
| sqlite_synth             | 2.93 us                                                | 2.74 us: 1.07x faster                                                |
| xml_etree_iterparse      | 111 ms                                                 | 104 ms: 1.07x faster                                                 |
| nqueens                  | 100 ms                                                 | 93.7 ms: 1.07x faster                                                |
| pathlib                  | 20.0 ms                                                | 18.8 ms: 1.06x faster                                                |
| unpickle                 | 14.1 us                                                | 13.9 us: 1.02x faster                                                |
| pidigits                 | 190 ms                                                 | 187 ms: 1.01x faster                                                 |
| meteor_contest           | 115 ms                                                 | 113 ms: 1.01x faster                                                 |
| regex_dna                | 222 ms                                                 | 222 ms: 1.00x slower                                                 |
| pickle_list              | 4.56 us                                                | 4.62 us: 1.01x slower                                                |
| regex_v8                 | 25.0 ms                                                | 25.4 ms: 1.01x slower                                                |
| unpickle_list            | 4.82 us                                                | 4.99 us: 1.03x slower                                                |
| pickle                   | 10.3 us                                                | 10.7 us: 1.04x slower                                                |
| async_generators         | 425 ms                                                 | 475 ms: 1.12x slower                                                 |
| regex_effbot             | 3.23 ms                                                | 3.63 ms: 1.12x slower                                                |
| pickle_dict              | 27.3 us                                                | 31.7 us: 1.16x slower                                                |
| coverage                 | 72.8 ms                                                | 87.0 ms: 1.20x slower                                                |
| python_startup_no_site   | 5.82 ms                                                | 7.32 ms: 1.26x slower                                                |
| dask                     | 423 ms                                                 | 532 ms: 1.26x slower                                                 |
| telco                    | 6.54 ms                                                | 8.25 ms: 1.26x slower                                                |
| Geometric mean           | (ref)                                                  | 1.26x faster                                                         |

Benchmark hidden because not significant (2): bench_mp_pool, gc_traversal
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.21x
- 95% likely to have a speedup of 1.21x
- 99% likely to have a speedup of 1.17x
