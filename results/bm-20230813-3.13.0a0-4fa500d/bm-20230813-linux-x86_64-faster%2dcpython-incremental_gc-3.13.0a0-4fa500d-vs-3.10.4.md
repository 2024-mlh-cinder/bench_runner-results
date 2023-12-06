
# Results vs. 3.10.4

- fork: faster-cpython
- ref: incremental_gc
- machine: linux-x86_64
- commit hash: 4fa500d
- commit date: 2023-08-13
- overall geometric mean: 1.33x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.24x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230813-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-4fa500d |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.39 sec: 1.33x faster                                                    |
| tornado_http   | 127 ms                                                 | 93.4 ms: 1.36x faster                                                     |
| Geometric mean | (ref)                                                  | 1.35x faster                                                              |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230813-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-4fa500d |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 88.9 ms: 1.59x faster                                                     |
| float          | 111 ms                                                 | 76.0 ms: 1.46x faster                                                     |
| pidigits       | 190 ms                                                 | 201 ms: 1.06x slower                                                      |
| Geometric mean | (ref)                                                  | 1.30x faster                                                              |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230813-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-4fa500d |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 136 ms: 1.30x faster                                                      |
| regex_dna      | 222 ms                                                 | 225 ms: 1.01x slower                                                      |
| regex_v8       | 25.0 ms                                                | 26.5 ms: 1.06x slower                                                     |
| regex_effbot   | 3.23 ms                                                | 3.69 ms: 1.14x slower                                                     |
| Geometric mean | (ref)                                                  | 1.01x faster                                                              |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230813-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-4fa500d |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 298 us: 1.53x faster                                                      |
| unpickle_pure_python | 300 us                                                 | 212 us: 1.41x faster                                                      |
| tomli_loads          | 2.92 sec                                               | 2.10 sec: 1.39x faster                                                    |
| json_dumps           | 13.5 ms                                                | 9.82 ms: 1.38x faster                                                     |
| xml_etree_process    | 74.9 ms                                                | 56.8 ms: 1.32x faster                                                     |
| xml_etree_generate   | 94.2 ms                                                | 81.9 ms: 1.15x faster                                                     |
| json_loads           | 28.8 us                                                | 25.2 us: 1.14x faster                                                     |
| xml_etree_iterparse  | 111 ms                                                 | 98.6 ms: 1.13x faster                                                     |
| xml_etree_parse      | 163 ms                                                 | 151 ms: 1.08x faster                                                      |
| unpickle             | 14.1 us                                                | 14.3 us: 1.01x slower                                                     |
| unpickle_list        | 4.82 us                                                | 5.15 us: 1.07x slower                                                     |
| pickle_dict          | 27.3 us                                                | 31.4 us: 1.15x slower                                                     |
| Geometric mean       | (ref)                                                  | 1.15x faster                                                              |

Benchmark hidden because not significant (2): pickle, pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230813-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-4fa500d |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 9.20 ms: 1.54x faster                                                     |
| python_startup_no_site | 5.82 ms                                                | 6.72 ms: 1.15x slower                                                     |
| Geometric mean         | (ref)                                                  | 1.15x faster                                                              |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230813-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-4fa500d |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 10.8 ms: 1.37x faster                                                     |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230813-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-4fa500d |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 143 us: 3.57x faster                                                      |
| async_tree_io            | 1.77 sec                                               | 608 ms: 2.92x faster                                                      |
| generators               | 76.8 ms                                                | 29.5 ms: 2.60x faster                                                     |
| async_tree_none          | 717 ms                                                 | 313 ms: 2.29x faster                                                      |
| deltablue                | 7.42 ms                                                | 3.26 ms: 2.27x faster                                                     |
| async_tree_memoization   | 854 ms                                                 | 383 ms: 2.23x faster                                                      |
| asyncio_tcp              | 925 ms                                                 | 475 ms: 1.95x faster                                                      |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 531 ms: 1.79x faster                                                      |
| chaos                    | 106 ms                                                 | 59.7 ms: 1.78x faster                                                     |
| crypto_pyaes             | 118 ms                                                 | 69.2 ms: 1.71x faster                                                     |
| richards_super           | 90.7 ms                                                | 53.3 ms: 1.70x faster                                                     |
| raytrace                 | 464 ms                                                 | 273 ms: 1.70x faster                                                      |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.79 sec: 1.68x faster                                                    |
| logging_silent           | 175 ns                                                 | 105 ns: 1.66x faster                                                      |
| scimark_monte_carlo      | 108 ms                                                 | 65.5 ms: 1.65x faster                                                     |
| sqlglot_parse            | 2.06 ms                                                | 1.26 ms: 1.63x faster                                                     |
| go                       | 229 ms                                                 | 141 ms: 1.63x faster                                                      |
| scimark_sor              | 197 ms                                                 | 121 ms: 1.63x faster                                                      |
| nbody                    | 142 ms                                                 | 88.9 ms: 1.59x faster                                                     |
| hexiom                   | 9.53 ms                                                | 5.98 ms: 1.59x faster                                                     |
| richards                 | 74.9 ms                                                | 47.4 ms: 1.58x faster                                                     |
| sqlglot_transpile        | 2.45 ms                                                | 1.58 ms: 1.55x faster                                                     |
| python_startup           | 14.2 ms                                                | 9.20 ms: 1.54x faster                                                     |
| pickle_pure_python       | 455 us                                                 | 298 us: 1.53x faster                                                      |
| pyflate                  | 673 ms                                                 | 448 ms: 1.50x faster                                                      |
| scimark_lu               | 163 ms                                                 | 112 ms: 1.46x faster                                                      |
| float                    | 111 ms                                                 | 76.0 ms: 1.46x faster                                                     |
| spectral_norm            | 150 ms                                                 | 105 ms: 1.42x faster                                                      |
| coroutines               | 31.8 ms                                                | 22.4 ms: 1.42x faster                                                     |
| unpickle_pure_python     | 300 us                                                 | 212 us: 1.41x faster                                                      |
| unpack_sequence          | 64.7 ns                                                | 46.1 ns: 1.41x faster                                                     |
| deepcopy_memo            | 52.3 us                                                | 37.6 us: 1.39x faster                                                     |
| tomli_loads              | 2.92 sec                                               | 2.10 sec: 1.39x faster                                                    |
| logging_simple           | 8.07 us                                                | 5.84 us: 1.38x faster                                                     |
| json_dumps               | 13.5 ms                                                | 9.82 ms: 1.38x faster                                                     |
| logging_format           | 8.91 us                                                | 6.46 us: 1.38x faster                                                     |
| mako                     | 14.8 ms                                                | 10.8 ms: 1.37x faster                                                     |
| tornado_http             | 127 ms                                                 | 93.4 ms: 1.36x faster                                                     |
| pprint_pformat           | 1.99 sec                                               | 1.49 sec: 1.33x faster                                                    |
| docutils                 | 3.17 sec                                               | 2.39 sec: 1.33x faster                                                    |
| xml_etree_process        | 74.9 ms                                                | 56.8 ms: 1.32x faster                                                     |
| pprint_safe_repr         | 955 ms                                                 | 727 ms: 1.31x faster                                                      |
| comprehensions           | 26.8 us                                                | 20.5 us: 1.31x faster                                                     |
| pycparser                | 1.50 sec                                               | 1.15 sec: 1.31x faster                                                    |
| regex_compile            | 177 ms                                                 | 136 ms: 1.30x faster                                                      |
| sqlglot_normalize        | 135 ms                                                 | 105 ms: 1.29x faster                                                      |
| deepcopy                 | 442 us                                                 | 353 us: 1.25x faster                                                      |
| sqlglot_optimize         | 65.3 ms                                                | 52.7 ms: 1.24x faster                                                     |
| nqueens                  | 100 ms                                                 | 80.7 ms: 1.24x faster                                                     |
| mypy2                    | 428 ms                                                 | 347 ms: 1.23x faster                                                      |
| fannkuch                 | 486 ms                                                 | 394 ms: 1.23x faster                                                      |
| deepcopy_reduce          | 3.82 us                                                | 3.16 us: 1.21x faster                                                     |
| scimark_fft              | 424 ms                                                 | 353 ms: 1.20x faster                                                      |
| bench_thread_pool        | 947 us                                                 | 814 us: 1.16x faster                                                      |
| create_gc_cycles         | 1.67 ms                                                | 1.44 ms: 1.16x faster                                                     |
| xml_etree_generate       | 94.2 ms                                                | 81.9 ms: 1.15x faster                                                     |
| dulwich_log              | 75.9 ms                                                | 66.2 ms: 1.15x faster                                                     |
| json_loads               | 28.8 us                                                | 25.2 us: 1.14x faster                                                     |
| json                     | 5.42 ms                                                | 4.79 ms: 1.13x faster                                                     |
| xml_etree_iterparse      | 111 ms                                                 | 98.6 ms: 1.13x faster                                                     |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.83 ms: 1.13x faster                                                     |
| mdp                      | 2.82 sec                                               | 2.52 sec: 1.12x faster                                                    |
| meteor_contest           | 115 ms                                                 | 106 ms: 1.08x faster                                                      |
| pathlib                  | 20.0 ms                                                | 18.5 ms: 1.08x faster                                                     |
| xml_etree_parse          | 163 ms                                                 | 151 ms: 1.08x faster                                                      |
| sqlite_synth             | 2.93 us                                                | 2.74 us: 1.07x faster                                                     |
| gc_traversal             | 3.84 ms                                                | 3.66 ms: 1.05x faster                                                     |
| bench_mp_pool            | 24.0 ms                                                | 24.0 ms: 1.00x slower                                                     |
| unpickle                 | 14.1 us                                                | 14.3 us: 1.01x slower                                                     |
| async_generators         | 425 ms                                                 | 429 ms: 1.01x slower                                                      |
| regex_dna                | 222 ms                                                 | 225 ms: 1.01x slower                                                      |
| pidigits                 | 190 ms                                                 | 201 ms: 1.06x slower                                                      |
| regex_v8                 | 25.0 ms                                                | 26.5 ms: 1.06x slower                                                     |
| unpickle_list            | 4.82 us                                                | 5.15 us: 1.07x slower                                                     |
| regex_effbot             | 3.23 ms                                                | 3.69 ms: 1.14x slower                                                     |
| pickle_dict              | 27.3 us                                                | 31.4 us: 1.15x slower                                                     |
| python_startup_no_site   | 5.82 ms                                                | 6.72 ms: 1.15x slower                                                     |
| dask                     | 423 ms                                                 | 501 ms: 1.18x slower                                                      |
| coverage                 | 72.8 ms                                                | 86.5 ms: 1.19x slower                                                     |
| telco                    | 6.54 ms                                                | 8.09 ms: 1.24x slower                                                     |
| Geometric mean           | (ref)                                                  | 1.33x faster                                                              |

Benchmark hidden because not significant (2): pickle, pickle_list
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.29x
- 95% likely to have a speedup of 1.28x
- 99% likely to have a speedup of 1.24x
