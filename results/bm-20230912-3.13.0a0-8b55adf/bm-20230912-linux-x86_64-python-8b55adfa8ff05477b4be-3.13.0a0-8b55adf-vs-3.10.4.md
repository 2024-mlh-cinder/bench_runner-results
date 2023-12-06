
# Results vs. 3.10.4

- fork: python
- ref: 8b55adfa8ff05477b4be
- machine: linux-x86_64
- commit hash: 8b55adf
- commit date: 2023-09-12
- overall geometric mean: 1.30x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.23x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230912-linux-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.61 sec: 1.21x faster                                                |
| tornado_http   | 127 ms                                                 | 95.4 ms: 1.34x faster                                                 |
| Geometric mean | (ref)                                                  | 1.27x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230912-linux-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 89.8 ms: 1.58x faster                                                 |
| float          | 111 ms                                                 | 80.5 ms: 1.37x faster                                                 |
| pidigits       | 190 ms                                                 | 187 ms: 1.02x faster                                                  |
| Geometric mean | (ref)                                                  | 1.30x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230912-linux-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 135 ms: 1.31x faster                                                  |
| regex_dna      | 222 ms                                                 | 214 ms: 1.03x faster                                                  |
| regex_v8       | 25.0 ms                                                | 24.6 ms: 1.02x faster                                                 |
| regex_effbot   | 3.23 ms                                                | 3.58 ms: 1.11x slower                                                 |
| Geometric mean | (ref)                                                  | 1.06x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230912-linux-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 302 us: 1.51x faster                                                  |
| tomli_loads          | 2.92 sec                                               | 2.07 sec: 1.41x faster                                                |
| json_dumps           | 13.5 ms                                                | 9.86 ms: 1.37x faster                                                 |
| unpickle_pure_python | 300 us                                                 | 221 us: 1.36x faster                                                  |
| xml_etree_process    | 74.9 ms                                                | 58.0 ms: 1.29x faster                                                 |
| json_loads           | 28.8 us                                                | 25.3 us: 1.14x faster                                                 |
| xml_etree_generate   | 94.2 ms                                                | 84.6 ms: 1.11x faster                                                 |
| xml_etree_iterparse  | 111 ms                                                 | 102 ms: 1.09x faster                                                  |
| xml_etree_parse      | 163 ms                                                 | 152 ms: 1.07x faster                                                  |
| pickle_list          | 4.56 us                                                | 4.53 us: 1.01x faster                                                 |
| unpickle             | 14.1 us                                                | 14.5 us: 1.03x slower                                                 |
| pickle               | 10.3 us                                                | 10.8 us: 1.05x slower                                                 |
| pickle_dict          | 27.3 us                                                | 32.5 us: 1.19x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.14x faster                                                          |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230912-linux-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.1 ms: 1.40x faster                                                 |
| python_startup_no_site | 5.82 ms                                                | 6.85 ms: 1.18x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.09x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230912-linux-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 10.9 ms: 1.35x faster                                                 |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230912-linux-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 146 us: 3.50x faster                                                  |
| generators               | 76.8 ms                                                | 29.1 ms: 2.64x faster                                                 |
| deltablue                | 7.42 ms                                                | 3.32 ms: 2.24x faster                                                 |
| asyncio_tcp              | 925 ms                                                 | 491 ms: 1.88x faster                                                  |
| chaos                    | 106 ms                                                 | 60.6 ms: 1.75x faster                                                 |
| logging_silent           | 175 ns                                                 | 102 ns: 1.72x faster                                                  |
| raytrace                 | 464 ms                                                 | 270 ms: 1.71x faster                                                  |
| crypto_pyaes             | 118 ms                                                 | 69.9 ms: 1.69x faster                                                 |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.79 sec: 1.68x faster                                                |
| richards_super           | 90.7 ms                                                | 54.8 ms: 1.65x faster                                                 |
| go                       | 229 ms                                                 | 140 ms: 1.64x faster                                                  |
| async_tree_none          | 717 ms                                                 | 438 ms: 1.64x faster                                                  |
| scimark_monte_carlo      | 108 ms                                                 | 66.4 ms: 1.63x faster                                                 |
| sqlglot_parse            | 2.06 ms                                                | 1.27 ms: 1.62x faster                                                 |
| scimark_sor              | 197 ms                                                 | 123 ms: 1.60x faster                                                  |
| hexiom                   | 9.53 ms                                                | 6.03 ms: 1.58x faster                                                 |
| nbody                    | 142 ms                                                 | 89.8 ms: 1.58x faster                                                 |
| richards                 | 74.9 ms                                                | 47.6 ms: 1.57x faster                                                 |
| sqlglot_transpile        | 2.45 ms                                                | 1.58 ms: 1.55x faster                                                 |
| async_tree_memoization   | 854 ms                                                 | 567 ms: 1.51x faster                                                  |
| pickle_pure_python       | 455 us                                                 | 302 us: 1.51x faster                                                  |
| scimark_lu               | 163 ms                                                 | 109 ms: 1.50x faster                                                  |
| async_tree_io            | 1.77 sec                                               | 1.19 sec: 1.49x faster                                                |
| pyflate                  | 673 ms                                                 | 459 ms: 1.47x faster                                                  |
| unpack_sequence          | 64.7 ns                                                | 45.0 ns: 1.44x faster                                                 |
| coroutines               | 31.8 ms                                                | 22.2 ms: 1.43x faster                                                 |
| deepcopy_memo            | 52.3 us                                                | 36.8 us: 1.42x faster                                                 |
| spectral_norm            | 150 ms                                                 | 106 ms: 1.41x faster                                                  |
| tomli_loads              | 2.92 sec                                               | 2.07 sec: 1.41x faster                                                |
| python_startup           | 14.2 ms                                                | 10.1 ms: 1.40x faster                                                 |
| json_dumps               | 13.5 ms                                                | 9.86 ms: 1.37x faster                                                 |
| float                    | 111 ms                                                 | 80.5 ms: 1.37x faster                                                 |
| unpickle_pure_python     | 300 us                                                 | 221 us: 1.36x faster                                                  |
| pprint_pformat           | 1.99 sec                                               | 1.46 sec: 1.36x faster                                                |
| mako                     | 14.8 ms                                                | 10.9 ms: 1.35x faster                                                 |
| logging_simple           | 8.07 us                                                | 5.98 us: 1.35x faster                                                 |
| logging_format           | 8.91 us                                                | 6.63 us: 1.34x faster                                                 |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 709 ms: 1.34x faster                                                  |
| tornado_http             | 127 ms                                                 | 95.4 ms: 1.34x faster                                                 |
| pprint_safe_repr         | 955 ms                                                 | 721 ms: 1.32x faster                                                  |
| comprehensions           | 26.8 us                                                | 20.3 us: 1.32x faster                                                 |
| regex_compile            | 177 ms                                                 | 135 ms: 1.31x faster                                                  |
| sqlglot_normalize        | 135 ms                                                 | 104 ms: 1.30x faster                                                  |
| xml_etree_process        | 74.9 ms                                                | 58.0 ms: 1.29x faster                                                 |
| deepcopy                 | 442 us                                                 | 345 us: 1.28x faster                                                  |
| mypy2                    | 428 ms                                                 | 339 ms: 1.26x faster                                                  |
| pycparser                | 1.50 sec                                               | 1.19 sec: 1.26x faster                                                |
| nqueens                  | 100 ms                                                 | 79.5 ms: 1.26x faster                                                 |
| sqlglot_optimize         | 65.3 ms                                                | 52.6 ms: 1.24x faster                                                 |
| deepcopy_reduce          | 3.82 us                                                | 3.10 us: 1.24x faster                                                 |
| fannkuch                 | 486 ms                                                 | 395 ms: 1.23x faster                                                  |
| docutils                 | 3.17 sec                                               | 2.61 sec: 1.21x faster                                                |
| scimark_fft              | 424 ms                                                 | 353 ms: 1.20x faster                                                  |
| bench_thread_pool        | 947 us                                                 | 809 us: 1.17x faster                                                  |
| json_loads               | 28.8 us                                                | 25.3 us: 1.14x faster                                                 |
| dulwich_log              | 75.9 ms                                                | 66.6 ms: 1.14x faster                                                 |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.79 ms: 1.14x faster                                                 |
| json                     | 5.42 ms                                                | 4.78 ms: 1.13x faster                                                 |
| mdp                      | 2.82 sec                                               | 2.53 sec: 1.11x faster                                                |
| xml_etree_generate       | 94.2 ms                                                | 84.6 ms: 1.11x faster                                                 |
| pathlib                  | 20.0 ms                                                | 18.3 ms: 1.09x faster                                                 |
| create_gc_cycles         | 1.67 ms                                                | 1.53 ms: 1.09x faster                                                 |
| xml_etree_iterparse      | 111 ms                                                 | 102 ms: 1.09x faster                                                  |
| meteor_contest           | 115 ms                                                 | 106 ms: 1.09x faster                                                  |
| xml_etree_parse          | 163 ms                                                 | 152 ms: 1.07x faster                                                  |
| sqlite_synth             | 2.93 us                                                | 2.77 us: 1.06x faster                                                 |
| regex_dna                | 222 ms                                                 | 214 ms: 1.03x faster                                                  |
| regex_v8                 | 25.0 ms                                                | 24.6 ms: 1.02x faster                                                 |
| pidigits                 | 190 ms                                                 | 187 ms: 1.02x faster                                                  |
| pickle_list              | 4.56 us                                                | 4.53 us: 1.01x faster                                                 |
| bench_mp_pool            | 24.0 ms                                                | 24.0 ms: 1.00x slower                                                 |
| unpickle                 | 14.1 us                                                | 14.5 us: 1.03x slower                                                 |
| gc_traversal             | 3.84 ms                                                | 4.00 ms: 1.04x slower                                                 |
| async_generators         | 425 ms                                                 | 443 ms: 1.04x slower                                                  |
| pickle                   | 10.3 us                                                | 10.8 us: 1.05x slower                                                 |
| regex_effbot             | 3.23 ms                                                | 3.58 ms: 1.11x slower                                                 |
| python_startup_no_site   | 5.82 ms                                                | 6.85 ms: 1.18x slower                                                 |
| coverage                 | 72.8 ms                                                | 85.7 ms: 1.18x slower                                                 |
| pickle_dict              | 27.3 us                                                | 32.5 us: 1.19x slower                                                 |
| dask                     | 423 ms                                                 | 526 ms: 1.25x slower                                                  |
| telco                    | 6.54 ms                                                | 8.23 ms: 1.26x slower                                                 |
| Geometric mean           | (ref)                                                  | 1.30x faster                                                          |

Benchmark hidden because not significant (1): unpickle_list
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.27x
- 95% likely to have a speedup of 1.25x
- 99% likely to have a speedup of 1.23x
