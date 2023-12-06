
# Results vs. 3.10.4

- fork: brandtbucher
- ref: 5e9259d5db5f6e94cadc
- machine: linux-x86_64
- commit hash: 5e9259d
- commit date: 2023-09-24
- overall geometric mean: 1.29x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.23x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.67 sec: 1.19x faster                                                      |
| tornado_http   | 127 ms                                                 | 95.9 ms: 1.33x faster                                                       |
| Geometric mean | (ref)                                                  | 1.26x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 91.7 ms: 1.54x faster                                                       |
| float          | 111 ms                                                 | 81.0 ms: 1.37x faster                                                       |
| pidigits       | 190 ms                                                 | 187 ms: 1.01x faster                                                        |
| Geometric mean | (ref)                                                  | 1.29x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 140 ms: 1.27x faster                                                        |
| regex_v8       | 25.0 ms                                                | 23.2 ms: 1.08x faster                                                       |
| regex_dna      | 222 ms                                                 | 210 ms: 1.06x faster                                                        |
| regex_effbot   | 3.23 ms                                                | 3.57 ms: 1.10x slower                                                       |
| Geometric mean | (ref)                                                  | 1.07x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 300 us: 1.52x faster                                                        |
| tomli_loads          | 2.92 sec                                               | 2.01 sec: 1.45x faster                                                      |
| json_dumps           | 13.5 ms                                                | 9.80 ms: 1.38x faster                                                       |
| unpickle_pure_python | 300 us                                                 | 227 us: 1.33x faster                                                        |
| xml_etree_process    | 74.9 ms                                                | 58.0 ms: 1.29x faster                                                       |
| json_loads           | 28.8 us                                                | 25.6 us: 1.13x faster                                                       |
| xml_etree_generate   | 94.2 ms                                                | 84.0 ms: 1.12x faster                                                       |
| xml_etree_iterparse  | 111 ms                                                 | 102 ms: 1.09x faster                                                        |
| xml_etree_parse      | 163 ms                                                 | 150 ms: 1.09x faster                                                        |
| unpickle_list        | 4.82 us                                                | 4.76 us: 1.01x faster                                                       |
| pickle_list          | 4.56 us                                                | 4.63 us: 1.02x slower                                                       |
| pickle_dict          | 27.3 us                                                | 30.8 us: 1.13x slower                                                       |
| Geometric mean       | (ref)                                                  | 1.15x faster                                                                |

Benchmark hidden because not significant (2): pickle, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.1 ms: 1.40x faster                                                       |
| python_startup_no_site | 5.82 ms                                                | 6.87 ms: 1.18x slower                                                       |
| Geometric mean         | (ref)                                                  | 1.09x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 10.8 ms: 1.37x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 145 us: 3.51x faster                                                        |
| generators               | 76.8 ms                                                | 28.5 ms: 2.70x faster                                                       |
| deltablue                | 7.42 ms                                                | 3.40 ms: 2.18x faster                                                       |
| asyncio_tcp              | 925 ms                                                 | 497 ms: 1.86x faster                                                        |
| logging_silent           | 175 ns                                                 | 102 ns: 1.71x faster                                                        |
| raytrace                 | 464 ms                                                 | 274 ms: 1.69x faster                                                        |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.79 sec: 1.68x faster                                                      |
| crypto_pyaes             | 118 ms                                                 | 70.9 ms: 1.67x faster                                                       |
| richards_super           | 90.7 ms                                                | 54.3 ms: 1.67x faster                                                       |
| chaos                    | 106 ms                                                 | 64.7 ms: 1.64x faster                                                       |
| scimark_sor              | 197 ms                                                 | 121 ms: 1.63x faster                                                        |
| async_tree_none          | 717 ms                                                 | 445 ms: 1.61x faster                                                        |
| scimark_monte_carlo      | 108 ms                                                 | 67.6 ms: 1.60x faster                                                       |
| sqlglot_parse            | 2.06 ms                                                | 1.29 ms: 1.60x faster                                                       |
| go                       | 229 ms                                                 | 147 ms: 1.55x faster                                                        |
| richards                 | 74.9 ms                                                | 48.4 ms: 1.55x faster                                                       |
| nbody                    | 142 ms                                                 | 91.7 ms: 1.54x faster                                                       |
| unpack_sequence          | 64.7 ns                                                | 42.0 ns: 1.54x faster                                                       |
| pickle_pure_python       | 455 us                                                 | 300 us: 1.52x faster                                                        |
| sqlglot_transpile        | 2.45 ms                                                | 1.61 ms: 1.52x faster                                                       |
| async_tree_memoization   | 854 ms                                                 | 569 ms: 1.50x faster                                                        |
| async_tree_io            | 1.77 sec                                               | 1.19 sec: 1.49x faster                                                      |
| pyflate                  | 673 ms                                                 | 459 ms: 1.47x faster                                                        |
| tomli_loads              | 2.92 sec                                               | 2.01 sec: 1.45x faster                                                      |
| scimark_lu               | 163 ms                                                 | 113 ms: 1.44x faster                                                        |
| hexiom                   | 9.53 ms                                                | 6.64 ms: 1.43x faster                                                       |
| coroutines               | 31.8 ms                                                | 22.4 ms: 1.42x faster                                                       |
| python_startup           | 14.2 ms                                                | 10.1 ms: 1.40x faster                                                       |
| spectral_norm            | 150 ms                                                 | 108 ms: 1.38x faster                                                        |
| json_dumps               | 13.5 ms                                                | 9.80 ms: 1.38x faster                                                       |
| mako                     | 14.8 ms                                                | 10.8 ms: 1.37x faster                                                       |
| float                    | 111 ms                                                 | 81.0 ms: 1.37x faster                                                       |
| deepcopy_memo            | 52.3 us                                                | 38.4 us: 1.36x faster                                                       |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 712 ms: 1.34x faster                                                        |
| tornado_http             | 127 ms                                                 | 95.9 ms: 1.33x faster                                                       |
| logging_format           | 8.91 us                                                | 6.72 us: 1.33x faster                                                       |
| unpickle_pure_python     | 300 us                                                 | 227 us: 1.33x faster                                                        |
| logging_simple           | 8.07 us                                                | 6.13 us: 1.32x faster                                                       |
| pprint_pformat           | 1.99 sec                                               | 1.52 sec: 1.31x faster                                                      |
| pprint_safe_repr         | 955 ms                                                 | 738 ms: 1.29x faster                                                        |
| xml_etree_process        | 74.9 ms                                                | 58.0 ms: 1.29x faster                                                       |
| pycparser                | 1.50 sec                                               | 1.18 sec: 1.27x faster                                                      |
| sqlglot_normalize        | 135 ms                                                 | 107 ms: 1.27x faster                                                        |
| regex_compile            | 177 ms                                                 | 140 ms: 1.27x faster                                                        |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.37 ms: 1.25x faster                                                       |
| scimark_fft              | 424 ms                                                 | 340 ms: 1.24x faster                                                        |
| deepcopy                 | 442 us                                                 | 355 us: 1.24x faster                                                        |
| mypy2                    | 428 ms                                                 | 348 ms: 1.23x faster                                                        |
| fannkuch                 | 486 ms                                                 | 395 ms: 1.23x faster                                                        |
| sqlglot_optimize         | 65.3 ms                                                | 53.8 ms: 1.21x faster                                                       |
| deepcopy_reduce          | 3.82 us                                                | 3.19 us: 1.20x faster                                                       |
| docutils                 | 3.17 sec                                               | 2.67 sec: 1.19x faster                                                      |
| comprehensions           | 26.8 us                                                | 22.8 us: 1.18x faster                                                       |
| nqueens                  | 100 ms                                                 | 85.3 ms: 1.17x faster                                                       |
| bench_thread_pool        | 947 us                                                 | 829 us: 1.14x faster                                                        |
| json_loads               | 28.8 us                                                | 25.6 us: 1.13x faster                                                       |
| dulwich_log              | 75.9 ms                                                | 67.5 ms: 1.12x faster                                                       |
| xml_etree_generate       | 94.2 ms                                                | 84.0 ms: 1.12x faster                                                       |
| create_gc_cycles         | 1.67 ms                                                | 1.51 ms: 1.11x faster                                                       |
| json                     | 5.42 ms                                                | 4.92 ms: 1.10x faster                                                       |
| xml_etree_iterparse      | 111 ms                                                 | 102 ms: 1.09x faster                                                        |
| xml_etree_parse          | 163 ms                                                 | 150 ms: 1.09x faster                                                        |
| regex_v8                 | 25.0 ms                                                | 23.2 ms: 1.08x faster                                                       |
| pathlib                  | 20.0 ms                                                | 18.7 ms: 1.07x faster                                                       |
| meteor_contest           | 115 ms                                                 | 108 ms: 1.06x faster                                                        |
| regex_dna                | 222 ms                                                 | 210 ms: 1.06x faster                                                        |
| sqlite_synth             | 2.93 us                                                | 2.79 us: 1.05x faster                                                       |
| mdp                      | 2.82 sec                                               | 2.75 sec: 1.03x faster                                                      |
| pidigits                 | 190 ms                                                 | 187 ms: 1.01x faster                                                        |
| unpickle_list            | 4.82 us                                                | 4.76 us: 1.01x faster                                                       |
| bench_mp_pool            | 24.0 ms                                                | 24.0 ms: 1.00x slower                                                       |
| pickle_list              | 4.56 us                                                | 4.63 us: 1.02x slower                                                       |
| async_generators         | 425 ms                                                 | 464 ms: 1.09x slower                                                        |
| gc_traversal             | 3.84 ms                                                | 4.21 ms: 1.10x slower                                                       |
| regex_effbot             | 3.23 ms                                                | 3.57 ms: 1.10x slower                                                       |
| pickle_dict              | 27.3 us                                                | 30.8 us: 1.13x slower                                                       |
| coverage                 | 72.8 ms                                                | 84.5 ms: 1.16x slower                                                       |
| python_startup_no_site   | 5.82 ms                                                | 6.87 ms: 1.18x slower                                                       |
| telco                    | 6.54 ms                                                | 8.13 ms: 1.24x slower                                                       |
| dask                     | 423 ms                                                 | 531 ms: 1.26x slower                                                        |
| Geometric mean           | (ref)                                                  | 1.29x faster                                                                |

Benchmark hidden because not significant (2): pickle, unpickle
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.25x
- 95% likely to have a speedup of 1.24x
- 99% likely to have a speedup of 1.23x
