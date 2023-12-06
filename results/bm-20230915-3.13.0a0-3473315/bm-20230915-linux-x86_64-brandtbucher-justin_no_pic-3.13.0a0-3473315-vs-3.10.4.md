
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_no_pic
- machine: linux-x86_64
- commit hash: 3473315
- commit date: 2023-09-15
- overall geometric mean: 1.29x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.21x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.67 sec: 1.19x faster                                               |
| tornado_http   | 127 ms                                                 | 96.8 ms: 1.32x faster                                                |
| Geometric mean | (ref)                                                  | 1.25x faster                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 87.9 ms: 1.61x faster                                                |
| float          | 111 ms                                                 | 81.5 ms: 1.36x faster                                                |
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                                 |
| Geometric mean | (ref)                                                  | 1.30x faster                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 142 ms: 1.25x faster                                                 |
| regex_dna      | 222 ms                                                 | 204 ms: 1.09x faster                                                 |
| regex_v8       | 25.0 ms                                                | 23.4 ms: 1.07x faster                                                |
| regex_effbot   | 3.23 ms                                                | 3.40 ms: 1.05x slower                                                |
| Geometric mean | (ref)                                                  | 1.08x faster                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 300 us: 1.52x faster                                                 |
| tomli_loads          | 2.92 sec                                               | 2.06 sec: 1.41x faster                                               |
| json_dumps           | 13.5 ms                                                | 9.77 ms: 1.38x faster                                                |
| unpickle_pure_python | 300 us                                                 | 225 us: 1.33x faster                                                 |
| xml_etree_process    | 74.9 ms                                                | 57.4 ms: 1.30x faster                                                |
| json_loads           | 28.8 us                                                | 25.3 us: 1.14x faster                                                |
| xml_etree_generate   | 94.2 ms                                                | 83.4 ms: 1.13x faster                                                |
| xml_etree_iterparse  | 111 ms                                                 | 102 ms: 1.09x faster                                                 |
| xml_etree_parse      | 163 ms                                                 | 152 ms: 1.07x faster                                                 |
| unpickle_list        | 4.82 us                                                | 4.87 us: 1.01x slower                                                |
| pickle_list          | 4.56 us                                                | 4.64 us: 1.02x slower                                                |
| pickle_dict          | 27.3 us                                                | 31.2 us: 1.14x slower                                                |
| Geometric mean       | (ref)                                                  | 1.14x faster                                                         |

Benchmark hidden because not significant (2): unpickle, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.0 ms: 1.41x faster                                                |
| python_startup_no_site | 5.82 ms                                                | 6.82 ms: 1.17x slower                                                |
| Geometric mean         | (ref)                                                  | 1.10x faster                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 10.9 ms: 1.35x faster                                                |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 147 us: 3.46x faster                                                 |
| generators               | 76.8 ms                                                | 28.5 ms: 2.69x faster                                                |
| deltablue                | 7.42 ms                                                | 3.38 ms: 2.20x faster                                                |
| asyncio_tcp              | 925 ms                                                 | 487 ms: 1.90x faster                                                 |
| raytrace                 | 464 ms                                                 | 270 ms: 1.72x faster                                                 |
| logging_silent           | 175 ns                                                 | 103 ns: 1.70x faster                                                 |
| richards_super           | 90.7 ms                                                | 53.7 ms: 1.69x faster                                                |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.81 sec: 1.66x faster                                               |
| crypto_pyaes             | 118 ms                                                 | 71.6 ms: 1.65x faster                                                |
| scimark_sor              | 197 ms                                                 | 119 ms: 1.65x faster                                                 |
| chaos                    | 106 ms                                                 | 64.3 ms: 1.65x faster                                                |
| async_tree_none          | 717 ms                                                 | 438 ms: 1.64x faster                                                 |
| scimark_monte_carlo      | 108 ms                                                 | 66.5 ms: 1.63x faster                                                |
| nbody                    | 142 ms                                                 | 87.9 ms: 1.61x faster                                                |
| sqlglot_parse            | 2.06 ms                                                | 1.28 ms: 1.61x faster                                                |
| go                       | 229 ms                                                 | 144 ms: 1.59x faster                                                 |
| richards                 | 74.9 ms                                                | 47.6 ms: 1.57x faster                                                |
| sqlglot_transpile        | 2.45 ms                                                | 1.59 ms: 1.54x faster                                                |
| pickle_pure_python       | 455 us                                                 | 300 us: 1.52x faster                                                 |
| async_tree_memoization   | 854 ms                                                 | 567 ms: 1.51x faster                                                 |
| async_tree_io            | 1.77 sec                                               | 1.19 sec: 1.49x faster                                               |
| pyflate                  | 673 ms                                                 | 456 ms: 1.48x faster                                                 |
| coroutines               | 31.8 ms                                                | 21.8 ms: 1.46x faster                                                |
| scimark_lu               | 163 ms                                                 | 112 ms: 1.45x faster                                                 |
| deepcopy_memo            | 52.3 us                                                | 37.0 us: 1.42x faster                                                |
| tomli_loads              | 2.92 sec                                               | 2.06 sec: 1.41x faster                                               |
| python_startup           | 14.2 ms                                                | 10.0 ms: 1.41x faster                                                |
| hexiom                   | 9.53 ms                                                | 6.80 ms: 1.40x faster                                                |
| spectral_norm            | 150 ms                                                 | 108 ms: 1.39x faster                                                 |
| json_dumps               | 13.5 ms                                                | 9.77 ms: 1.38x faster                                                |
| unpack_sequence          | 64.7 ns                                                | 46.9 ns: 1.38x faster                                                |
| logging_simple           | 8.07 us                                                | 5.94 us: 1.36x faster                                                |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 701 ms: 1.36x faster                                                 |
| float                    | 111 ms                                                 | 81.5 ms: 1.36x faster                                                |
| mako                     | 14.8 ms                                                | 10.9 ms: 1.35x faster                                                |
| pprint_pformat           | 1.99 sec                                               | 1.48 sec: 1.34x faster                                               |
| logging_format           | 8.91 us                                                | 6.66 us: 1.34x faster                                                |
| unpickle_pure_python     | 300 us                                                 | 225 us: 1.33x faster                                                 |
| pprint_safe_repr         | 955 ms                                                 | 717 ms: 1.33x faster                                                 |
| tornado_http             | 127 ms                                                 | 96.8 ms: 1.32x faster                                                |
| pycparser                | 1.50 sec                                               | 1.15 sec: 1.31x faster                                               |
| xml_etree_process        | 74.9 ms                                                | 57.4 ms: 1.30x faster                                                |
| sqlglot_normalize        | 135 ms                                                 | 106 ms: 1.27x faster                                                 |
| deepcopy                 | 442 us                                                 | 351 us: 1.26x faster                                                 |
| regex_compile            | 177 ms                                                 | 142 ms: 1.25x faster                                                 |
| scimark_fft              | 424 ms                                                 | 340 ms: 1.25x faster                                                 |
| deepcopy_reduce          | 3.82 us                                                | 3.10 us: 1.24x faster                                                |
| mypy2                    | 428 ms                                                 | 350 ms: 1.23x faster                                                 |
| sqlglot_optimize         | 65.3 ms                                                | 53.4 ms: 1.22x faster                                                |
| comprehensions           | 26.8 us                                                | 22.5 us: 1.19x faster                                                |
| docutils                 | 3.17 sec                                               | 2.67 sec: 1.19x faster                                               |
| fannkuch                 | 486 ms                                                 | 409 ms: 1.19x faster                                                 |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.69 ms: 1.16x faster                                                |
| nqueens                  | 100 ms                                                 | 87.8 ms: 1.14x faster                                                |
| json_loads               | 28.8 us                                                | 25.3 us: 1.14x faster                                                |
| bench_thread_pool        | 947 us                                                 | 834 us: 1.14x faster                                                 |
| xml_etree_generate       | 94.2 ms                                                | 83.4 ms: 1.13x faster                                                |
| create_gc_cycles         | 1.67 ms                                                | 1.50 ms: 1.11x faster                                                |
| dulwich_log              | 75.9 ms                                                | 68.7 ms: 1.11x faster                                                |
| xml_etree_iterparse      | 111 ms                                                 | 102 ms: 1.09x faster                                                 |
| regex_dna                | 222 ms                                                 | 204 ms: 1.09x faster                                                 |
| json                     | 5.42 ms                                                | 5.02 ms: 1.08x faster                                                |
| xml_etree_parse          | 163 ms                                                 | 152 ms: 1.07x faster                                                 |
| regex_v8                 | 25.0 ms                                                | 23.4 ms: 1.07x faster                                                |
| sqlite_synth             | 2.93 us                                                | 2.75 us: 1.07x faster                                                |
| pathlib                  | 20.0 ms                                                | 18.7 ms: 1.07x faster                                                |
| meteor_contest           | 115 ms                                                 | 109 ms: 1.05x faster                                                 |
| mdp                      | 2.82 sec                                               | 2.73 sec: 1.03x faster                                               |
| pidigits                 | 190 ms                                                 | 188 ms: 1.01x faster                                                 |
| gc_traversal             | 3.84 ms                                                | 3.84 ms: 1.00x slower                                                |
| unpickle_list            | 4.82 us                                                | 4.87 us: 1.01x slower                                                |
| pickle_list              | 4.56 us                                                | 4.64 us: 1.02x slower                                                |
| regex_effbot             | 3.23 ms                                                | 3.40 ms: 1.05x slower                                                |
| async_generators         | 425 ms                                                 | 458 ms: 1.08x slower                                                 |
| pickle_dict              | 27.3 us                                                | 31.2 us: 1.14x slower                                                |
| coverage                 | 72.8 ms                                                | 84.5 ms: 1.16x slower                                                |
| python_startup_no_site   | 5.82 ms                                                | 6.82 ms: 1.17x slower                                                |
| telco                    | 6.54 ms                                                | 7.92 ms: 1.21x slower                                                |
| dask                     | 423 ms                                                 | 529 ms: 1.25x slower                                                 |
| Geometric mean           | (ref)                                                  | 1.29x faster                                                         |

Benchmark hidden because not significant (3): unpickle, bench_mp_pool, pickle
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.26x
- 95% likely to have a speedup of 1.24x
- 99% likely to have a speedup of 1.21x
