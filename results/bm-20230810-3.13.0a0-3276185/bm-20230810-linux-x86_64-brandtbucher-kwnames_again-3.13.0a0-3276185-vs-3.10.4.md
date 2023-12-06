
# Results vs. 3.10.4

- fork: brandtbucher
- ref: kwnames_again
- machine: linux-x86_64
- commit hash: 3276185
- commit date: 2023-08-10
- overall geometric mean: 1.27x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.21x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.66 sec: 1.19x faster                                               |
| tornado_http   | 127 ms                                                 | 97.7 ms: 1.30x faster                                                |
| Geometric mean | (ref)                                                  | 1.25x faster                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 92.5 ms: 1.53x faster                                                |
| float          | 111 ms                                                 | 79.3 ms: 1.39x faster                                                |
| pidigits       | 190 ms                                                 | 201 ms: 1.06x slower                                                 |
| Geometric mean | (ref)                                                  | 1.26x faster                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 140 ms: 1.26x faster                                                 |
| regex_dna      | 222 ms                                                 | 224 ms: 1.01x slower                                                 |
| regex_effbot   | 3.23 ms                                                | 3.76 ms: 1.16x slower                                                |
| regex_v8       | 25.0 ms                                                | 29.2 ms: 1.17x slower                                                |
| Geometric mean | (ref)                                                  | 1.02x slower                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 308 us: 1.48x faster                                                 |
| json_dumps           | 13.5 ms                                                | 9.84 ms: 1.37x faster                                                |
| unpickle_pure_python | 300 us                                                 | 220 us: 1.36x faster                                                 |
| tomli_loads          | 2.92 sec                                               | 2.18 sec: 1.34x faster                                               |
| xml_etree_process    | 74.9 ms                                                | 57.9 ms: 1.29x faster                                                |
| json_loads           | 28.8 us                                                | 25.3 us: 1.14x faster                                                |
| xml_etree_generate   | 94.2 ms                                                | 83.4 ms: 1.13x faster                                                |
| xml_etree_iterparse  | 111 ms                                                 | 103 ms: 1.08x faster                                                 |
| xml_etree_parse      | 163 ms                                                 | 152 ms: 1.08x faster                                                 |
| pickle_list          | 4.56 us                                                | 4.64 us: 1.02x slower                                                |
| pickle               | 10.3 us                                                | 10.6 us: 1.03x slower                                                |
| unpickle_list        | 4.82 us                                                | 5.13 us: 1.06x slower                                                |
| unpickle             | 14.1 us                                                | 15.1 us: 1.07x slower                                                |
| pickle_dict          | 27.3 us                                                | 32.1 us: 1.18x slower                                                |
| Geometric mean       | (ref)                                                  | 1.12x faster                                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 9.38 ms: 1.51x faster                                                |
| python_startup_no_site | 5.82 ms                                                | 6.86 ms: 1.18x slower                                                |
| Geometric mean         | (ref)                                                  | 1.13x faster                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 11.3 ms: 1.31x faster                                                |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 151 us: 3.38x faster                                                 |
| generators               | 76.8 ms                                                | 29.9 ms: 2.56x faster                                                |
| deltablue                | 7.42 ms                                                | 3.38 ms: 2.19x faster                                                |
| asyncio_tcp              | 925 ms                                                 | 484 ms: 1.91x faster                                                 |
| chaos                    | 106 ms                                                 | 61.6 ms: 1.72x faster                                                |
| crypto_pyaes             | 118 ms                                                 | 70.2 ms: 1.69x faster                                                |
| logging_silent           | 175 ns                                                 | 104 ns: 1.68x faster                                                 |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.79 sec: 1.68x faster                                               |
| raytrace                 | 464 ms                                                 | 279 ms: 1.66x faster                                                 |
| richards_super           | 90.7 ms                                                | 55.1 ms: 1.65x faster                                                |
| async_tree_none          | 717 ms                                                 | 446 ms: 1.61x faster                                                 |
| scimark_monte_carlo      | 108 ms                                                 | 67.3 ms: 1.61x faster                                                |
| go                       | 229 ms                                                 | 143 ms: 1.61x faster                                                 |
| scimark_sor              | 197 ms                                                 | 123 ms: 1.59x faster                                                 |
| sqlglot_parse            | 2.06 ms                                                | 1.30 ms: 1.58x faster                                                |
| nbody                    | 142 ms                                                 | 92.5 ms: 1.53x faster                                                |
| richards                 | 74.9 ms                                                | 49.0 ms: 1.53x faster                                                |
| sqlglot_transpile        | 2.45 ms                                                | 1.62 ms: 1.51x faster                                                |
| python_startup           | 14.2 ms                                                | 9.38 ms: 1.51x faster                                                |
| async_tree_io            | 1.77 sec                                               | 1.19 sec: 1.50x faster                                               |
| async_tree_memoization   | 854 ms                                                 | 572 ms: 1.49x faster                                                 |
| hexiom                   | 9.53 ms                                                | 6.39 ms: 1.49x faster                                                |
| pickle_pure_python       | 455 us                                                 | 308 us: 1.48x faster                                                 |
| pyflate                  | 673 ms                                                 | 457 ms: 1.47x faster                                                 |
| scimark_lu               | 163 ms                                                 | 112 ms: 1.46x faster                                                 |
| coroutines               | 31.8 ms                                                | 22.7 ms: 1.40x faster                                                |
| float                    | 111 ms                                                 | 79.3 ms: 1.39x faster                                                |
| spectral_norm            | 150 ms                                                 | 109 ms: 1.38x faster                                                 |
| json_dumps               | 13.5 ms                                                | 9.84 ms: 1.37x faster                                                |
| unpickle_pure_python     | 300 us                                                 | 220 us: 1.36x faster                                                 |
| deepcopy_memo            | 52.3 us                                                | 38.7 us: 1.35x faster                                                |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 709 ms: 1.34x faster                                                 |
| tomli_loads              | 2.92 sec                                               | 2.18 sec: 1.34x faster                                               |
| mako                     | 14.8 ms                                                | 11.3 ms: 1.31x faster                                                |
| pprint_pformat           | 1.99 sec                                               | 1.52 sec: 1.31x faster                                               |
| tornado_http             | 127 ms                                                 | 97.7 ms: 1.30x faster                                                |
| xml_etree_process        | 74.9 ms                                                | 57.9 ms: 1.29x faster                                                |
| logging_simple           | 8.07 us                                                | 6.29 us: 1.28x faster                                                |
| pprint_safe_repr         | 955 ms                                                 | 745 ms: 1.28x faster                                                 |
| logging_format           | 8.91 us                                                | 7.02 us: 1.27x faster                                                |
| sqlglot_normalize        | 135 ms                                                 | 107 ms: 1.26x faster                                                 |
| regex_compile            | 177 ms                                                 | 140 ms: 1.26x faster                                                 |
| mypy2                    | 428 ms                                                 | 344 ms: 1.25x faster                                                 |
| comprehensions           | 26.8 us                                                | 21.5 us: 1.25x faster                                                |
| fannkuch                 | 486 ms                                                 | 391 ms: 1.24x faster                                                 |
| pycparser                | 1.50 sec                                               | 1.22 sec: 1.23x faster                                               |
| deepcopy                 | 442 us                                                 | 361 us: 1.22x faster                                                 |
| sqlglot_optimize         | 65.3 ms                                                | 53.7 ms: 1.22x faster                                                |
| nqueens                  | 100 ms                                                 | 82.3 ms: 1.22x faster                                                |
| unpack_sequence          | 64.7 ns                                                | 53.6 ns: 1.21x faster                                                |
| deepcopy_reduce          | 3.82 us                                                | 3.19 us: 1.20x faster                                                |
| docutils                 | 3.17 sec                                               | 2.66 sec: 1.19x faster                                               |
| scimark_fft              | 424 ms                                                 | 359 ms: 1.18x faster                                                 |
| bench_thread_pool        | 947 us                                                 | 825 us: 1.15x faster                                                 |
| create_gc_cycles         | 1.67 ms                                                | 1.46 ms: 1.14x faster                                                |
| json_loads               | 28.8 us                                                | 25.3 us: 1.14x faster                                                |
| xml_etree_generate       | 94.2 ms                                                | 83.4 ms: 1.13x faster                                                |
| json                     | 5.42 ms                                                | 4.83 ms: 1.12x faster                                                |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.87 ms: 1.12x faster                                                |
| dulwich_log              | 75.9 ms                                                | 68.1 ms: 1.11x faster                                                |
| mdp                      | 2.82 sec                                               | 2.56 sec: 1.10x faster                                               |
| meteor_contest           | 115 ms                                                 | 105 ms: 1.09x faster                                                 |
| xml_etree_iterparse      | 111 ms                                                 | 103 ms: 1.08x faster                                                 |
| xml_etree_parse          | 163 ms                                                 | 152 ms: 1.08x faster                                                 |
| sqlite_synth             | 2.93 us                                                | 2.73 us: 1.07x faster                                                |
| pathlib                  | 20.0 ms                                                | 19.0 ms: 1.05x faster                                                |
| regex_dna                | 222 ms                                                 | 224 ms: 1.01x slower                                                 |
| pickle_list              | 4.56 us                                                | 4.64 us: 1.02x slower                                                |
| pickle                   | 10.3 us                                                | 10.6 us: 1.03x slower                                                |
| async_generators         | 425 ms                                                 | 448 ms: 1.05x slower                                                 |
| pidigits                 | 190 ms                                                 | 201 ms: 1.06x slower                                                 |
| unpickle_list            | 4.82 us                                                | 5.13 us: 1.06x slower                                                |
| unpickle                 | 14.1 us                                                | 15.1 us: 1.07x slower                                                |
| gc_traversal             | 3.84 ms                                                | 4.14 ms: 1.08x slower                                                |
| regex_effbot             | 3.23 ms                                                | 3.76 ms: 1.16x slower                                                |
| regex_v8                 | 25.0 ms                                                | 29.2 ms: 1.17x slower                                                |
| pickle_dict              | 27.3 us                                                | 32.1 us: 1.18x slower                                                |
| python_startup_no_site   | 5.82 ms                                                | 6.86 ms: 1.18x slower                                                |
| coverage                 | 72.8 ms                                                | 87.5 ms: 1.20x slower                                                |
| telco                    | 6.54 ms                                                | 7.95 ms: 1.22x slower                                                |
| dask                     | 423 ms                                                 | 535 ms: 1.27x slower                                                 |
| Geometric mean           | (ref)                                                  | 1.27x faster                                                         |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.24x
- 95% likely to have a speedup of 1.23x
- 99% likely to have a speedup of 1.21x
