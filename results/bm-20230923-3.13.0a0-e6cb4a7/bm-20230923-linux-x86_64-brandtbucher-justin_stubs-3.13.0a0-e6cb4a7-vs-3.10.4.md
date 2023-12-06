
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_stubs
- machine: linux-x86_64
- commit hash: e6cb4a7
- commit date: 2023-09-23
- overall geometric mean: 1.28x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.21x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-linux-x86_64-brandtbucher-justin_stubs-3.13.0a0-e6cb4a7 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.69 sec: 1.18x faster                                              |
| tornado_http   | 127 ms                                                 | 97.0 ms: 1.31x faster                                               |
| Geometric mean | (ref)                                                  | 1.24x faster                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-linux-x86_64-brandtbucher-justin_stubs-3.13.0a0-e6cb4a7 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 90.9 ms: 1.56x faster                                               |
| float          | 111 ms                                                 | 82.5 ms: 1.34x faster                                               |
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                                |
| Geometric mean | (ref)                                                  | 1.28x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-linux-x86_64-brandtbucher-justin_stubs-3.13.0a0-e6cb4a7 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 143 ms: 1.23x faster                                                |
| regex_v8       | 25.0 ms                                                | 23.3 ms: 1.08x faster                                               |
| regex_dna      | 222 ms                                                 | 210 ms: 1.06x faster                                                |
| regex_effbot   | 3.23 ms                                                | 3.65 ms: 1.13x slower                                               |
| Geometric mean | (ref)                                                  | 1.06x faster                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-linux-x86_64-brandtbucher-justin_stubs-3.13.0a0-e6cb4a7 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 296 us: 1.54x faster                                                |
| tomli_loads          | 2.92 sec                                               | 2.07 sec: 1.41x faster                                              |
| json_dumps           | 13.5 ms                                                | 9.86 ms: 1.37x faster                                               |
| unpickle_pure_python | 300 us                                                 | 223 us: 1.35x faster                                                |
| xml_etree_process    | 74.9 ms                                                | 58.1 ms: 1.29x faster                                               |
| json_loads           | 28.8 us                                                | 25.2 us: 1.14x faster                                               |
| xml_etree_generate   | 94.2 ms                                                | 84.6 ms: 1.11x faster                                               |
| xml_etree_iterparse  | 111 ms                                                 | 103 ms: 1.08x faster                                                |
| xml_etree_parse      | 163 ms                                                 | 152 ms: 1.07x faster                                                |
| pickle_list          | 4.56 us                                                | 4.58 us: 1.01x slower                                               |
| unpickle_list        | 4.82 us                                                | 5.02 us: 1.04x slower                                               |
| unpickle             | 14.1 us                                                | 14.9 us: 1.05x slower                                               |
| pickle_dict          | 27.3 us                                                | 31.6 us: 1.16x slower                                               |
| Geometric mean       | (ref)                                                  | 1.14x faster                                                        |

Benchmark hidden because not significant (1): pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-linux-x86_64-brandtbucher-justin_stubs-3.13.0a0-e6cb4a7 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.1 ms: 1.40x faster                                               |
| python_startup_no_site | 5.82 ms                                                | 6.88 ms: 1.18x slower                                               |
| Geometric mean         | (ref)                                                  | 1.09x faster                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-linux-x86_64-brandtbucher-justin_stubs-3.13.0a0-e6cb4a7 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 11.0 ms: 1.34x faster                                               |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-linux-x86_64-brandtbucher-justin_stubs-3.13.0a0-e6cb4a7 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 148 us: 3.44x faster                                                |
| generators               | 76.8 ms                                                | 28.4 ms: 2.70x faster                                               |
| deltablue                | 7.42 ms                                                | 3.38 ms: 2.19x faster                                               |
| asyncio_tcp              | 925 ms                                                 | 503 ms: 1.84x faster                                                |
| raytrace                 | 464 ms                                                 | 271 ms: 1.71x faster                                                |
| richards_super           | 90.7 ms                                                | 54.1 ms: 1.68x faster                                               |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.80 sec: 1.67x faster                                              |
| crypto_pyaes             | 118 ms                                                 | 71.3 ms: 1.66x faster                                               |
| logging_silent           | 175 ns                                                 | 105 ns: 1.66x faster                                                |
| scimark_sor              | 197 ms                                                 | 120 ms: 1.65x faster                                                |
| chaos                    | 106 ms                                                 | 64.8 ms: 1.64x faster                                               |
| scimark_monte_carlo      | 108 ms                                                 | 66.2 ms: 1.64x faster                                               |
| async_tree_none          | 717 ms                                                 | 444 ms: 1.61x faster                                                |
| sqlglot_parse            | 2.06 ms                                                | 1.28 ms: 1.60x faster                                               |
| go                       | 229 ms                                                 | 145 ms: 1.58x faster                                                |
| nbody                    | 142 ms                                                 | 90.9 ms: 1.56x faster                                               |
| richards                 | 74.9 ms                                                | 48.2 ms: 1.55x faster                                               |
| pickle_pure_python       | 455 us                                                 | 296 us: 1.54x faster                                                |
| sqlglot_transpile        | 2.45 ms                                                | 1.61 ms: 1.52x faster                                               |
| async_tree_memoization   | 854 ms                                                 | 571 ms: 1.50x faster                                                |
| async_tree_io            | 1.77 sec                                               | 1.19 sec: 1.49x faster                                              |
| pyflate                  | 673 ms                                                 | 459 ms: 1.47x faster                                                |
| scimark_lu               | 163 ms                                                 | 112 ms: 1.46x faster                                                |
| coroutines               | 31.8 ms                                                | 21.9 ms: 1.45x faster                                               |
| tomli_loads              | 2.92 sec                                               | 2.07 sec: 1.41x faster                                              |
| python_startup           | 14.2 ms                                                | 10.1 ms: 1.40x faster                                               |
| hexiom                   | 9.53 ms                                                | 6.86 ms: 1.39x faster                                               |
| json_dumps               | 13.5 ms                                                | 9.86 ms: 1.37x faster                                               |
| spectral_norm            | 150 ms                                                 | 109 ms: 1.37x faster                                                |
| unpickle_pure_python     | 300 us                                                 | 223 us: 1.35x faster                                                |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 706 ms: 1.35x faster                                                |
| mako                     | 14.8 ms                                                | 11.0 ms: 1.34x faster                                               |
| float                    | 111 ms                                                 | 82.5 ms: 1.34x faster                                               |
| deepcopy_memo            | 52.3 us                                                | 39.1 us: 1.34x faster                                               |
| tornado_http             | 127 ms                                                 | 97.0 ms: 1.31x faster                                               |
| pprint_pformat           | 1.99 sec                                               | 1.52 sec: 1.30x faster                                              |
| unpack_sequence          | 64.7 ns                                                | 49.9 ns: 1.30x faster                                               |
| logging_simple           | 8.07 us                                                | 6.24 us: 1.29x faster                                               |
| xml_etree_process        | 74.9 ms                                                | 58.1 ms: 1.29x faster                                               |
| logging_format           | 8.91 us                                                | 6.92 us: 1.29x faster                                               |
| pprint_safe_repr         | 955 ms                                                 | 748 ms: 1.28x faster                                                |
| sqlglot_normalize        | 135 ms                                                 | 106 ms: 1.27x faster                                                |
| pycparser                | 1.50 sec                                               | 1.19 sec: 1.26x faster                                              |
| scimark_fft              | 424 ms                                                 | 341 ms: 1.24x faster                                                |
| deepcopy                 | 442 us                                                 | 357 us: 1.24x faster                                                |
| regex_compile            | 177 ms                                                 | 143 ms: 1.23x faster                                                |
| mypy2                    | 428 ms                                                 | 350 ms: 1.22x faster                                                |
| sqlglot_optimize         | 65.3 ms                                                | 53.6 ms: 1.22x faster                                               |
| fannkuch                 | 486 ms                                                 | 401 ms: 1.21x faster                                                |
| deepcopy_reduce          | 3.82 us                                                | 3.17 us: 1.21x faster                                               |
| docutils                 | 3.17 sec                                               | 2.69 sec: 1.18x faster                                              |
| comprehensions           | 26.8 us                                                | 23.0 us: 1.17x faster                                               |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.74 ms: 1.15x faster                                               |
| nqueens                  | 100 ms                                                 | 87.1 ms: 1.15x faster                                               |
| json_loads               | 28.8 us                                                | 25.2 us: 1.14x faster                                               |
| bench_thread_pool        | 947 us                                                 | 832 us: 1.14x faster                                                |
| json                     | 5.42 ms                                                | 4.86 ms: 1.11x faster                                               |
| xml_etree_generate       | 94.2 ms                                                | 84.6 ms: 1.11x faster                                               |
| dulwich_log              | 75.9 ms                                                | 68.3 ms: 1.11x faster                                               |
| create_gc_cycles         | 1.67 ms                                                | 1.53 ms: 1.09x faster                                               |
| xml_etree_iterparse      | 111 ms                                                 | 103 ms: 1.08x faster                                                |
| mdp                      | 2.82 sec                                               | 2.62 sec: 1.08x faster                                              |
| regex_v8                 | 25.0 ms                                                | 23.3 ms: 1.08x faster                                               |
| xml_etree_parse          | 163 ms                                                 | 152 ms: 1.07x faster                                                |
| pathlib                  | 20.0 ms                                                | 18.7 ms: 1.07x faster                                               |
| sqlite_synth             | 2.93 us                                                | 2.76 us: 1.06x faster                                               |
| regex_dna                | 222 ms                                                 | 210 ms: 1.06x faster                                                |
| meteor_contest           | 115 ms                                                 | 110 ms: 1.04x faster                                                |
| pidigits                 | 190 ms                                                 | 188 ms: 1.01x faster                                                |
| pickle_list              | 4.56 us                                                | 4.58 us: 1.01x slower                                               |
| unpickle_list            | 4.82 us                                                | 5.02 us: 1.04x slower                                               |
| unpickle                 | 14.1 us                                                | 14.9 us: 1.05x slower                                               |
| async_generators         | 425 ms                                                 | 464 ms: 1.09x slower                                                |
| regex_effbot             | 3.23 ms                                                | 3.65 ms: 1.13x slower                                               |
| gc_traversal             | 3.84 ms                                                | 4.37 ms: 1.14x slower                                               |
| pickle_dict              | 27.3 us                                                | 31.6 us: 1.16x slower                                               |
| python_startup_no_site   | 5.82 ms                                                | 6.88 ms: 1.18x slower                                               |
| coverage                 | 72.8 ms                                                | 86.7 ms: 1.19x slower                                               |
| telco                    | 6.54 ms                                                | 8.07 ms: 1.23x slower                                               |
| dask                     | 423 ms                                                 | 529 ms: 1.25x slower                                                |
| Geometric mean           | (ref)                                                  | 1.28x faster                                                        |

Benchmark hidden because not significant (2): bench_mp_pool, pickle
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.24x
- 95% likely to have a speedup of 1.23x
- 99% likely to have a speedup of 1.21x
