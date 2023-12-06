
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_small
- machine: linux-x86_64
- commit hash: 1710e5b
- commit date: 2023-09-17
- overall geometric mean: 1.30x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.22x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230917-linux-x86_64-brandtbucher-justin_small-3.13.0a0-1710e5b |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.64 sec: 1.20x faster                                              |
| tornado_http   | 127 ms                                                 | 96.0 ms: 1.33x faster                                               |
| Geometric mean | (ref)                                                  | 1.26x faster                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230917-linux-x86_64-brandtbucher-justin_small-3.13.0a0-1710e5b |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 83.7 ms: 1.69x faster                                               |
| float          | 111 ms                                                 | 81.5 ms: 1.36x faster                                               |
| pidigits       | 190 ms                                                 | 187 ms: 1.01x faster                                                |
| Geometric mean | (ref)                                                  | 1.32x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230917-linux-x86_64-brandtbucher-justin_small-3.13.0a0-1710e5b |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 138 ms: 1.28x faster                                                |
| regex_dna      | 222 ms                                                 | 204 ms: 1.09x faster                                                |
| regex_v8       | 25.0 ms                                                | 23.3 ms: 1.07x faster                                               |
| regex_effbot   | 3.23 ms                                                | 3.34 ms: 1.03x slower                                               |
| Geometric mean | (ref)                                                  | 1.10x faster                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230917-linux-x86_64-brandtbucher-justin_small-3.13.0a0-1710e5b |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 298 us: 1.53x faster                                                |
| tomli_loads          | 2.92 sec                                               | 1.98 sec: 1.47x faster                                              |
| json_dumps           | 13.5 ms                                                | 9.91 ms: 1.37x faster                                               |
| unpickle_pure_python | 300 us                                                 | 221 us: 1.36x faster                                                |
| xml_etree_process    | 74.9 ms                                                | 57.6 ms: 1.30x faster                                               |
| json_loads           | 28.8 us                                                | 25.1 us: 1.15x faster                                               |
| xml_etree_generate   | 94.2 ms                                                | 83.4 ms: 1.13x faster                                               |
| xml_etree_iterparse  | 111 ms                                                 | 103 ms: 1.08x faster                                                |
| xml_etree_parse      | 163 ms                                                 | 154 ms: 1.06x faster                                                |
| pickle_list          | 4.56 us                                                | 4.49 us: 1.02x faster                                               |
| unpickle_list        | 4.82 us                                                | 4.91 us: 1.02x slower                                               |
| pickle               | 10.3 us                                                | 10.6 us: 1.03x slower                                               |
| unpickle             | 14.1 us                                                | 14.8 us: 1.04x slower                                               |
| pickle_dict          | 27.3 us                                                | 31.6 us: 1.16x slower                                               |
| Geometric mean       | (ref)                                                  | 1.14x faster                                                        |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230917-linux-x86_64-brandtbucher-justin_small-3.13.0a0-1710e5b |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.1 ms: 1.40x faster                                               |
| python_startup_no_site | 5.82 ms                                                | 6.88 ms: 1.18x slower                                               |
| Geometric mean         | (ref)                                                  | 1.09x faster                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230917-linux-x86_64-brandtbucher-justin_small-3.13.0a0-1710e5b |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 10.8 ms: 1.36x faster                                               |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230917-linux-x86_64-brandtbucher-justin_small-3.13.0a0-1710e5b |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 146 us: 3.49x faster                                                |
| generators               | 76.8 ms                                                | 29.5 ms: 2.60x faster                                               |
| deltablue                | 7.42 ms                                                | 3.36 ms: 2.21x faster                                               |
| asyncio_tcp              | 925 ms                                                 | 501 ms: 1.85x faster                                                |
| raytrace                 | 464 ms                                                 | 268 ms: 1.73x faster                                                |
| chaos                    | 106 ms                                                 | 61.7 ms: 1.72x faster                                               |
| logging_silent           | 175 ns                                                 | 103 ns: 1.69x faster                                                |
| nbody                    | 142 ms                                                 | 83.7 ms: 1.69x faster                                               |
| richards_super           | 90.7 ms                                                | 54.0 ms: 1.68x faster                                               |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.81 sec: 1.66x faster                                              |
| scimark_sor              | 197 ms                                                 | 120 ms: 1.64x faster                                                |
| crypto_pyaes             | 118 ms                                                 | 72.4 ms: 1.64x faster                                               |
| scimark_monte_carlo      | 108 ms                                                 | 66.6 ms: 1.63x faster                                               |
| async_tree_none          | 717 ms                                                 | 443 ms: 1.62x faster                                                |
| sqlglot_parse            | 2.06 ms                                                | 1.28 ms: 1.61x faster                                               |
| richards                 | 74.9 ms                                                | 46.9 ms: 1.60x faster                                               |
| go                       | 229 ms                                                 | 145 ms: 1.58x faster                                                |
| sqlglot_transpile        | 2.45 ms                                                | 1.59 ms: 1.54x faster                                               |
| unpack_sequence          | 64.7 ns                                                | 42.4 ns: 1.53x faster                                               |
| pickle_pure_python       | 455 us                                                 | 298 us: 1.53x faster                                                |
| async_tree_memoization   | 854 ms                                                 | 565 ms: 1.51x faster                                                |
| async_tree_io            | 1.77 sec                                               | 1.19 sec: 1.49x faster                                              |
| tomli_loads              | 2.92 sec                                               | 1.98 sec: 1.47x faster                                              |
| pyflate                  | 673 ms                                                 | 459 ms: 1.47x faster                                                |
| hexiom                   | 9.53 ms                                                | 6.53 ms: 1.46x faster                                               |
| scimark_lu               | 163 ms                                                 | 113 ms: 1.45x faster                                                |
| coroutines               | 31.8 ms                                                | 22.2 ms: 1.43x faster                                               |
| python_startup           | 14.2 ms                                                | 10.1 ms: 1.40x faster                                               |
| deepcopy_memo            | 52.3 us                                                | 37.8 us: 1.39x faster                                               |
| spectral_norm            | 150 ms                                                 | 108 ms: 1.38x faster                                                |
| logging_format           | 8.91 us                                                | 6.45 us: 1.38x faster                                               |
| json_dumps               | 13.5 ms                                                | 9.91 ms: 1.37x faster                                               |
| logging_simple           | 8.07 us                                                | 5.92 us: 1.36x faster                                               |
| mako                     | 14.8 ms                                                | 10.8 ms: 1.36x faster                                               |
| unpickle_pure_python     | 300 us                                                 | 221 us: 1.36x faster                                                |
| float                    | 111 ms                                                 | 81.5 ms: 1.36x faster                                               |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 712 ms: 1.34x faster                                                |
| pprint_pformat           | 1.99 sec                                               | 1.49 sec: 1.33x faster                                              |
| tornado_http             | 127 ms                                                 | 96.0 ms: 1.33x faster                                               |
| pprint_safe_repr         | 955 ms                                                 | 725 ms: 1.32x faster                                                |
| xml_etree_process        | 74.9 ms                                                | 57.6 ms: 1.30x faster                                               |
| pycparser                | 1.50 sec                                               | 1.16 sec: 1.30x faster                                              |
| scimark_fft              | 424 ms                                                 | 331 ms: 1.28x faster                                                |
| regex_compile            | 177 ms                                                 | 138 ms: 1.28x faster                                                |
| sqlglot_normalize        | 135 ms                                                 | 106 ms: 1.28x faster                                                |
| deepcopy                 | 442 us                                                 | 352 us: 1.25x faster                                                |
| mypy2                    | 428 ms                                                 | 345 ms: 1.24x faster                                                |
| sqlglot_optimize         | 65.3 ms                                                | 53.2 ms: 1.23x faster                                               |
| deepcopy_reduce          | 3.82 us                                                | 3.15 us: 1.21x faster                                               |
| comprehensions           | 26.8 us                                                | 22.2 us: 1.21x faster                                               |
| docutils                 | 3.17 sec                                               | 2.64 sec: 1.20x faster                                              |
| fannkuch                 | 486 ms                                                 | 406 ms: 1.20x faster                                                |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.61 ms: 1.18x faster                                               |
| nqueens                  | 100 ms                                                 | 85.7 ms: 1.17x faster                                               |
| json_loads               | 28.8 us                                                | 25.1 us: 1.15x faster                                               |
| json                     | 5.42 ms                                                | 4.77 ms: 1.13x faster                                               |
| bench_thread_pool        | 947 us                                                 | 835 us: 1.13x faster                                                |
| xml_etree_generate       | 94.2 ms                                                | 83.4 ms: 1.13x faster                                               |
| dulwich_log              | 75.9 ms                                                | 67.4 ms: 1.13x faster                                               |
| mdp                      | 2.82 sec                                               | 2.58 sec: 1.10x faster                                              |
| create_gc_cycles         | 1.67 ms                                                | 1.53 ms: 1.09x faster                                               |
| regex_dna                | 222 ms                                                 | 204 ms: 1.09x faster                                                |
| xml_etree_iterparse      | 111 ms                                                 | 103 ms: 1.08x faster                                                |
| regex_v8                 | 25.0 ms                                                | 23.3 ms: 1.07x faster                                               |
| meteor_contest           | 115 ms                                                 | 107 ms: 1.07x faster                                                |
| pathlib                  | 20.0 ms                                                | 18.8 ms: 1.07x faster                                               |
| sqlite_synth             | 2.93 us                                                | 2.76 us: 1.06x faster                                               |
| xml_etree_parse          | 163 ms                                                 | 154 ms: 1.06x faster                                                |
| pickle_list              | 4.56 us                                                | 4.49 us: 1.02x faster                                               |
| pidigits                 | 190 ms                                                 | 187 ms: 1.01x faster                                                |
| unpickle_list            | 4.82 us                                                | 4.91 us: 1.02x slower                                               |
| pickle                   | 10.3 us                                                | 10.6 us: 1.03x slower                                               |
| regex_effbot             | 3.23 ms                                                | 3.34 ms: 1.03x slower                                               |
| gc_traversal             | 3.84 ms                                                | 3.98 ms: 1.04x slower                                               |
| unpickle                 | 14.1 us                                                | 14.8 us: 1.04x slower                                               |
| async_generators         | 425 ms                                                 | 459 ms: 1.08x slower                                                |
| pickle_dict              | 27.3 us                                                | 31.6 us: 1.16x slower                                               |
| python_startup_no_site   | 5.82 ms                                                | 6.88 ms: 1.18x slower                                               |
| coverage                 | 72.8 ms                                                | 86.4 ms: 1.19x slower                                               |
| telco                    | 6.54 ms                                                | 8.05 ms: 1.23x slower                                               |
| dask                     | 423 ms                                                 | 532 ms: 1.26x slower                                                |
| Geometric mean           | (ref)                                                  | 1.30x faster                                                        |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.27x
- 95% likely to have a speedup of 1.26x
- 99% likely to have a speedup of 1.22x
