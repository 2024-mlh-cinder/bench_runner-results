
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 51863b7
- commit date: 2023-09-23
- overall geometric mean: 1.30x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.23x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-linux-x86_64-python-main-3.13.0a0-51863b7 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.60 sec: 1.22x faster                                |
| tornado_http   | 127 ms                                                 | 94.9 ms: 1.34x faster                                 |
| Geometric mean | (ref)                                                  | 1.28x faster                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-linux-x86_64-python-main-3.13.0a0-51863b7 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| nbody          | 142 ms                                                 | 90.9 ms: 1.56x faster                                 |
| float          | 111 ms                                                 | 78.8 ms: 1.40x faster                                 |
| pidigits       | 190 ms                                                 | 187 ms: 1.02x faster                                  |
| Geometric mean | (ref)                                                  | 1.30x faster                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-linux-x86_64-python-main-3.13.0a0-51863b7 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 134 ms: 1.32x faster                                  |
| regex_dna      | 222 ms                                                 | 202 ms: 1.10x faster                                  |
| regex_v8       | 25.0 ms                                                | 24.0 ms: 1.05x faster                                 |
| regex_effbot   | 3.23 ms                                                | 3.36 ms: 1.04x slower                                 |
| Geometric mean | (ref)                                                  | 1.10x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-linux-x86_64-python-main-3.13.0a0-51863b7 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 296 us: 1.54x faster                                  |
| tomli_loads          | 2.92 sec                                               | 2.06 sec: 1.42x faster                                |
| unpickle_pure_python | 300 us                                                 | 215 us: 1.40x faster                                  |
| json_dumps           | 13.5 ms                                                | 9.77 ms: 1.39x faster                                 |
| xml_etree_process    | 74.9 ms                                                | 56.5 ms: 1.33x faster                                 |
| xml_etree_generate   | 94.2 ms                                                | 81.5 ms: 1.16x faster                                 |
| json_loads           | 28.8 us                                                | 25.4 us: 1.14x faster                                 |
| xml_etree_iterparse  | 111 ms                                                 | 102 ms: 1.10x faster                                  |
| xml_etree_parse      | 163 ms                                                 | 153 ms: 1.07x faster                                  |
| pickle               | 10.3 us                                                | 10.2 us: 1.01x faster                                 |
| unpickle             | 14.1 us                                                | 14.6 us: 1.04x slower                                 |
| pickle_list          | 4.56 us                                                | 4.75 us: 1.04x slower                                 |
| unpickle_list        | 4.82 us                                                | 5.03 us: 1.04x slower                                 |
| pickle_dict          | 27.3 us                                                | 31.6 us: 1.16x slower                                 |
| Geometric mean       | (ref)                                                  | 1.14x faster                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-linux-x86_64-python-main-3.13.0a0-51863b7 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.1 ms: 1.41x faster                                 |
| python_startup_no_site | 5.82 ms                                                | 6.86 ms: 1.18x slower                                 |
| Geometric mean         | (ref)                                                  | 1.09x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-linux-x86_64-python-main-3.13.0a0-51863b7 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 14.8 ms                                                | 10.9 ms: 1.36x faster                                 |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-linux-x86_64-python-main-3.13.0a0-51863b7 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 140 us: 3.66x faster                                  |
| generators               | 76.8 ms                                                | 29.5 ms: 2.60x faster                                 |
| deltablue                | 7.42 ms                                                | 3.34 ms: 2.22x faster                                 |
| asyncio_tcp              | 925 ms                                                 | 504 ms: 1.84x faster                                  |
| chaos                    | 106 ms                                                 | 60.2 ms: 1.77x faster                                 |
| logging_silent           | 175 ns                                                 | 100 ns: 1.74x faster                                  |
| raytrace                 | 464 ms                                                 | 271 ms: 1.71x faster                                  |
| crypto_pyaes             | 118 ms                                                 | 69.8 ms: 1.70x faster                                 |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.79 sec: 1.68x faster                                |
| richards_super           | 90.7 ms                                                | 54.2 ms: 1.67x faster                                 |
| async_tree_none          | 717 ms                                                 | 436 ms: 1.64x faster                                  |
| sqlglot_parse            | 2.06 ms                                                | 1.27 ms: 1.62x faster                                 |
| scimark_monte_carlo      | 108 ms                                                 | 67.2 ms: 1.61x faster                                 |
| go                       | 229 ms                                                 | 143 ms: 1.60x faster                                  |
| hexiom                   | 9.53 ms                                                | 5.99 ms: 1.59x faster                                 |
| richards                 | 74.9 ms                                                | 48.0 ms: 1.56x faster                                 |
| sqlglot_transpile        | 2.45 ms                                                | 1.57 ms: 1.56x faster                                 |
| nbody                    | 142 ms                                                 | 90.9 ms: 1.56x faster                                 |
| pickle_pure_python       | 455 us                                                 | 296 us: 1.54x faster                                  |
| async_tree_memoization   | 854 ms                                                 | 561 ms: 1.52x faster                                  |
| scimark_sor              | 197 ms                                                 | 130 ms: 1.51x faster                                  |
| async_tree_io            | 1.77 sec                                               | 1.18 sec: 1.51x faster                                |
| scimark_lu               | 163 ms                                                 | 111 ms: 1.47x faster                                  |
| pyflate                  | 673 ms                                                 | 462 ms: 1.46x faster                                  |
| deepcopy_memo            | 52.3 us                                                | 36.6 us: 1.43x faster                                 |
| coroutines               | 31.8 ms                                                | 22.3 ms: 1.43x faster                                 |
| tomli_loads              | 2.92 sec                                               | 2.06 sec: 1.42x faster                                |
| spectral_norm            | 150 ms                                                 | 106 ms: 1.41x faster                                  |
| python_startup           | 14.2 ms                                                | 10.1 ms: 1.41x faster                                 |
| float                    | 111 ms                                                 | 78.8 ms: 1.40x faster                                 |
| unpickle_pure_python     | 300 us                                                 | 215 us: 1.40x faster                                  |
| json_dumps               | 13.5 ms                                                | 9.77 ms: 1.39x faster                                 |
| logging_simple           | 8.07 us                                                | 5.92 us: 1.36x faster                                 |
| pprint_pformat           | 1.99 sec                                               | 1.46 sec: 1.36x faster                                |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 699 ms: 1.36x faster                                  |
| logging_format           | 8.91 us                                                | 6.57 us: 1.36x faster                                 |
| mako                     | 14.8 ms                                                | 10.9 ms: 1.36x faster                                 |
| unpack_sequence          | 64.7 ns                                                | 48.0 ns: 1.35x faster                                 |
| tornado_http             | 127 ms                                                 | 94.9 ms: 1.34x faster                                 |
| pprint_safe_repr         | 955 ms                                                 | 713 ms: 1.34x faster                                  |
| xml_etree_process        | 74.9 ms                                                | 56.5 ms: 1.33x faster                                 |
| comprehensions           | 26.8 us                                                | 20.3 us: 1.32x faster                                 |
| regex_compile            | 177 ms                                                 | 134 ms: 1.32x faster                                  |
| pycparser                | 1.50 sec                                               | 1.16 sec: 1.30x faster                                |
| sqlglot_normalize        | 135 ms                                                 | 105 ms: 1.29x faster                                  |
| deepcopy                 | 442 us                                                 | 344 us: 1.28x faster                                  |
| nqueens                  | 100 ms                                                 | 78.7 ms: 1.27x faster                                 |
| mypy2                    | 428 ms                                                 | 338 ms: 1.27x faster                                  |
| sqlglot_optimize         | 65.3 ms                                                | 52.6 ms: 1.24x faster                                 |
| deepcopy_reduce          | 3.82 us                                                | 3.09 us: 1.24x faster                                 |
| fannkuch                 | 486 ms                                                 | 393 ms: 1.24x faster                                  |
| docutils                 | 3.17 sec                                               | 2.60 sec: 1.22x faster                                |
| scimark_fft              | 424 ms                                                 | 353 ms: 1.20x faster                                  |
| bench_thread_pool        | 947 us                                                 | 805 us: 1.18x faster                                  |
| xml_etree_generate       | 94.2 ms                                                | 81.5 ms: 1.16x faster                                 |
| dulwich_log              | 75.9 ms                                                | 65.9 ms: 1.15x faster                                 |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.74 ms: 1.15x faster                                 |
| json_loads               | 28.8 us                                                | 25.4 us: 1.14x faster                                 |
| json                     | 5.42 ms                                                | 4.78 ms: 1.13x faster                                 |
| mdp                      | 2.82 sec                                               | 2.50 sec: 1.13x faster                                |
| xml_etree_iterparse      | 111 ms                                                 | 102 ms: 1.10x faster                                  |
| regex_dna                | 222 ms                                                 | 202 ms: 1.10x faster                                  |
| create_gc_cycles         | 1.67 ms                                                | 1.54 ms: 1.09x faster                                 |
| meteor_contest           | 115 ms                                                 | 106 ms: 1.09x faster                                  |
| xml_etree_parse          | 163 ms                                                 | 153 ms: 1.07x faster                                  |
| sqlite_synth             | 2.93 us                                                | 2.76 us: 1.07x faster                                 |
| pathlib                  | 20.0 ms                                                | 19.0 ms: 1.05x faster                                 |
| regex_v8                 | 25.0 ms                                                | 24.0 ms: 1.05x faster                                 |
| pidigits                 | 190 ms                                                 | 187 ms: 1.02x faster                                  |
| pickle                   | 10.3 us                                                | 10.2 us: 1.01x faster                                 |
| gc_traversal             | 3.84 ms                                                | 3.85 ms: 1.00x slower                                 |
| unpickle                 | 14.1 us                                                | 14.6 us: 1.04x slower                                 |
| regex_effbot             | 3.23 ms                                                | 3.36 ms: 1.04x slower                                 |
| pickle_list              | 4.56 us                                                | 4.75 us: 1.04x slower                                 |
| async_generators         | 425 ms                                                 | 443 ms: 1.04x slower                                  |
| unpickle_list            | 4.82 us                                                | 5.03 us: 1.04x slower                                 |
| pickle_dict              | 27.3 us                                                | 31.6 us: 1.16x slower                                 |
| python_startup_no_site   | 5.82 ms                                                | 6.86 ms: 1.18x slower                                 |
| coverage                 | 72.8 ms                                                | 87.8 ms: 1.21x slower                                 |
| telco                    | 6.54 ms                                                | 7.97 ms: 1.22x slower                                 |
| dask                     | 423 ms                                                 | 526 ms: 1.24x slower                                  |
| Geometric mean           | (ref)                                                  | 1.30x faster                                          |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.28x
- 95% likely to have a speedup of 1.27x
- 99% likely to have a speedup of 1.23x
