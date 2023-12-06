
# Results vs. 3.10.4

- fork: brandtbucher
- ref: break_up_float_reuse
- machine: linux-x86_64
- commit hash: 52776df
- commit date: 2023-10-17
- overall geometric mean: 1.27x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.21x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-52776df |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.64 sec: 1.20x faster                                                       |
| tornado_http   | 127 ms                                                 | 95.9 ms: 1.33x faster                                                        |
| Geometric mean | (ref)                                                  | 1.26x faster                                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-52776df |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 95.1 ms: 1.49x faster                                                        |
| float          | 111 ms                                                 | 81.6 ms: 1.35x faster                                                        |
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                                         |
| Geometric mean | (ref)                                                  | 1.27x faster                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-52776df |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 137 ms: 1.29x faster                                                         |
| regex_dna      | 222 ms                                                 | 214 ms: 1.04x faster                                                         |
| regex_v8       | 25.0 ms                                                | 25.6 ms: 1.02x slower                                                        |
| regex_effbot   | 3.23 ms                                                | 4.06 ms: 1.26x slower                                                        |
| Geometric mean | (ref)                                                  | 1.01x faster                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-52776df |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 309 us: 1.47x faster                                                         |
| tomli_loads          | 2.92 sec                                               | 2.16 sec: 1.35x faster                                                       |
| unpickle_pure_python | 300 us                                                 | 225 us: 1.33x faster                                                         |
| json_dumps           | 13.5 ms                                                | 10.4 ms: 1.30x faster                                                        |
| xml_etree_process    | 74.9 ms                                                | 59.5 ms: 1.26x faster                                                        |
| xml_etree_generate   | 94.2 ms                                                | 85.8 ms: 1.10x faster                                                        |
| xml_etree_iterparse  | 111 ms                                                 | 106 ms: 1.05x faster                                                         |
| json_loads           | 28.8 us                                                | 27.9 us: 1.03x faster                                                        |
| xml_etree_parse      | 163 ms                                                 | 159 ms: 1.03x faster                                                         |
| unpickle             | 14.1 us                                                | 14.3 us: 1.01x slower                                                        |
| unpickle_list        | 4.82 us                                                | 5.00 us: 1.04x slower                                                        |
| pickle_list          | 4.56 us                                                | 4.97 us: 1.09x slower                                                        |
| pickle               | 10.3 us                                                | 11.7 us: 1.14x slower                                                        |
| pickle_dict          | 27.3 us                                                | 35.6 us: 1.31x slower                                                        |
| Geometric mean       | (ref)                                                  | 1.08x faster                                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-52776df |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.0 ms: 1.41x faster                                                        |
| python_startup_no_site | 5.82 ms                                                | 6.82 ms: 1.17x slower                                                        |
| Geometric mean         | (ref)                                                  | 1.10x faster                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-52776df |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 12.0 ms: 1.23x faster                                                        |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-52776df |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 154 us: 3.32x faster                                                         |
| generators               | 76.8 ms                                                | 29.8 ms: 2.58x faster                                                        |
| deltablue                | 7.42 ms                                                | 3.32 ms: 2.24x faster                                                        |
| asyncio_tcp              | 925 ms                                                 | 478 ms: 1.94x faster                                                         |
| chaos                    | 106 ms                                                 | 62.0 ms: 1.71x faster                                                        |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.78 sec: 1.69x faster                                                       |
| richards_super           | 90.7 ms                                                | 54.8 ms: 1.66x faster                                                        |
| raytrace                 | 464 ms                                                 | 280 ms: 1.65x faster                                                         |
| async_tree_none          | 717 ms                                                 | 438 ms: 1.64x faster                                                         |
| crypto_pyaes             | 118 ms                                                 | 72.5 ms: 1.63x faster                                                        |
| logging_silent           | 175 ns                                                 | 108 ns: 1.61x faster                                                         |
| go                       | 229 ms                                                 | 143 ms: 1.60x faster                                                         |
| sqlglot_parse            | 2.06 ms                                                | 1.29 ms: 1.59x faster                                                        |
| scimark_monte_carlo      | 108 ms                                                 | 68.6 ms: 1.58x faster                                                        |
| richards                 | 74.9 ms                                                | 48.5 ms: 1.54x faster                                                        |
| sqlglot_transpile        | 2.45 ms                                                | 1.61 ms: 1.52x faster                                                        |
| async_tree_memoization   | 854 ms                                                 | 562 ms: 1.52x faster                                                         |
| unpack_sequence          | 64.7 ns                                                | 42.9 ns: 1.51x faster                                                        |
| hexiom                   | 9.53 ms                                                | 6.31 ms: 1.51x faster                                                        |
| async_tree_io            | 1.77 sec                                               | 1.18 sec: 1.50x faster                                                       |
| nbody                    | 142 ms                                                 | 95.1 ms: 1.49x faster                                                        |
| scimark_sor              | 197 ms                                                 | 132 ms: 1.49x faster                                                         |
| pickle_pure_python       | 455 us                                                 | 309 us: 1.47x faster                                                         |
| pyflate                  | 673 ms                                                 | 459 ms: 1.47x faster                                                         |
| scimark_lu               | 163 ms                                                 | 115 ms: 1.42x faster                                                         |
| python_startup           | 14.2 ms                                                | 10.0 ms: 1.41x faster                                                        |
| coroutines               | 31.8 ms                                                | 22.7 ms: 1.40x faster                                                        |
| logging_format           | 8.91 us                                                | 6.43 us: 1.39x faster                                                        |
| logging_simple           | 8.07 us                                                | 5.91 us: 1.37x faster                                                        |
| float                    | 111 ms                                                 | 81.6 ms: 1.35x faster                                                        |
| tomli_loads              | 2.92 sec                                               | 2.16 sec: 1.35x faster                                                       |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 711 ms: 1.34x faster                                                         |
| deepcopy_memo            | 52.3 us                                                | 39.2 us: 1.34x faster                                                        |
| unpickle_pure_python     | 300 us                                                 | 225 us: 1.33x faster                                                         |
| tornado_http             | 127 ms                                                 | 95.9 ms: 1.33x faster                                                        |
| spectral_norm            | 150 ms                                                 | 113 ms: 1.33x faster                                                         |
| pprint_pformat           | 1.99 sec                                               | 1.52 sec: 1.31x faster                                                       |
| json_dumps               | 13.5 ms                                                | 10.4 ms: 1.30x faster                                                        |
| comprehensions           | 26.8 us                                                | 20.8 us: 1.29x faster                                                        |
| regex_compile            | 177 ms                                                 | 137 ms: 1.29x faster                                                         |
| sqlglot_normalize        | 135 ms                                                 | 106 ms: 1.27x faster                                                         |
| pprint_safe_repr         | 955 ms                                                 | 753 ms: 1.27x faster                                                         |
| xml_etree_process        | 74.9 ms                                                | 59.5 ms: 1.26x faster                                                        |
| mypy2                    | 428 ms                                                 | 342 ms: 1.25x faster                                                         |
| pycparser                | 1.50 sec                                               | 1.21 sec: 1.24x faster                                                       |
| deepcopy                 | 442 us                                                 | 357 us: 1.24x faster                                                         |
| mako                     | 14.8 ms                                                | 12.0 ms: 1.23x faster                                                        |
| nqueens                  | 100 ms                                                 | 81.3 ms: 1.23x faster                                                        |
| sqlglot_optimize         | 65.3 ms                                                | 53.6 ms: 1.22x faster                                                        |
| docutils                 | 3.17 sec                                               | 2.64 sec: 1.20x faster                                                       |
| deepcopy_reduce          | 3.82 us                                                | 3.21 us: 1.19x faster                                                        |
| bench_thread_pool        | 947 us                                                 | 811 us: 1.17x faster                                                         |
| scimark_fft              | 424 ms                                                 | 369 ms: 1.15x faster                                                         |
| create_gc_cycles         | 1.67 ms                                                | 1.46 ms: 1.15x faster                                                        |
| fannkuch                 | 486 ms                                                 | 424 ms: 1.15x faster                                                         |
| dulwich_log              | 75.9 ms                                                | 66.7 ms: 1.14x faster                                                        |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.82 ms: 1.13x faster                                                        |
| xml_etree_generate       | 94.2 ms                                                | 85.8 ms: 1.10x faster                                                        |
| mdp                      | 2.82 sec                                               | 2.58 sec: 1.09x faster                                                       |
| meteor_contest           | 115 ms                                                 | 109 ms: 1.06x faster                                                         |
| json                     | 5.42 ms                                                | 5.13 ms: 1.06x faster                                                        |
| xml_etree_iterparse      | 111 ms                                                 | 106 ms: 1.05x faster                                                         |
| pathlib                  | 20.0 ms                                                | 19.2 ms: 1.04x faster                                                        |
| regex_dna                | 222 ms                                                 | 214 ms: 1.04x faster                                                         |
| json_loads               | 28.8 us                                                | 27.9 us: 1.03x faster                                                        |
| sqlite_synth             | 2.93 us                                                | 2.85 us: 1.03x faster                                                        |
| xml_etree_parse          | 163 ms                                                 | 159 ms: 1.03x faster                                                         |
| pidigits                 | 190 ms                                                 | 188 ms: 1.01x faster                                                         |
| unpickle                 | 14.1 us                                                | 14.3 us: 1.01x slower                                                        |
| regex_v8                 | 25.0 ms                                                | 25.6 ms: 1.02x slower                                                        |
| unpickle_list            | 4.82 us                                                | 5.00 us: 1.04x slower                                                        |
| gc_traversal             | 3.84 ms                                                | 4.04 ms: 1.05x slower                                                        |
| async_generators         | 425 ms                                                 | 462 ms: 1.09x slower                                                         |
| pickle_list              | 4.56 us                                                | 4.97 us: 1.09x slower                                                        |
| pickle                   | 10.3 us                                                | 11.7 us: 1.14x slower                                                        |
| python_startup_no_site   | 5.82 ms                                                | 6.82 ms: 1.17x slower                                                        |
| coverage                 | 72.8 ms                                                | 91.1 ms: 1.25x slower                                                        |
| regex_effbot             | 3.23 ms                                                | 4.06 ms: 1.26x slower                                                        |
| telco                    | 6.54 ms                                                | 8.26 ms: 1.26x slower                                                        |
| pickle_dict              | 27.3 us                                                | 35.6 us: 1.31x slower                                                        |
| Geometric mean           | (ref)                                                  | 1.27x faster                                                                 |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (19) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.25x
- 95% likely to have a speedup of 1.23x
- 99% likely to have a speedup of 1.21x
