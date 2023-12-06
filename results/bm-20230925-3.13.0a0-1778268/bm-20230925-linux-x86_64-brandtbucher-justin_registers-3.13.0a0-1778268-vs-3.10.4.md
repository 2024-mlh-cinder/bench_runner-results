
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: 1778268
- commit date: 2023-09-25
- overall geometric mean: 1.26x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.17x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.68 sec: 1.18x faster                                                  |
| tornado_http   | 127 ms                                                 | 99.1 ms: 1.29x faster                                                   |
| Geometric mean | (ref)                                                  | 1.23x faster                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 103 ms: 1.38x faster                                                    |
| float          | 111 ms                                                 | 86.8 ms: 1.27x faster                                                   |
| pidigits       | 190 ms                                                 | 195 ms: 1.03x slower                                                    |
| Geometric mean | (ref)                                                  | 1.20x faster                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 149 ms: 1.19x faster                                                    |
| regex_dna      | 222 ms                                                 | 205 ms: 1.08x faster                                                    |
| regex_v8       | 25.0 ms                                                | 23.4 ms: 1.07x faster                                                   |
| regex_effbot   | 3.23 ms                                                | 3.40 ms: 1.05x slower                                                   |
| Geometric mean | (ref)                                                  | 1.07x faster                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 303 us: 1.50x faster                                                    |
| json_dumps           | 13.5 ms                                                | 9.87 ms: 1.37x faster                                                   |
| tomli_loads          | 2.92 sec                                               | 2.15 sec: 1.36x faster                                                  |
| xml_etree_process    | 74.9 ms                                                | 57.4 ms: 1.31x faster                                                   |
| unpickle_pure_python | 300 us                                                 | 233 us: 1.29x faster                                                    |
| json_loads           | 28.8 us                                                | 25.0 us: 1.15x faster                                                   |
| xml_etree_generate   | 94.2 ms                                                | 83.2 ms: 1.13x faster                                                   |
| xml_etree_parse      | 163 ms                                                 | 151 ms: 1.08x faster                                                    |
| xml_etree_iterparse  | 111 ms                                                 | 107 ms: 1.04x faster                                                    |
| pickle               | 10.3 us                                                | 10.6 us: 1.03x slower                                                   |
| pickle_list          | 4.56 us                                                | 4.72 us: 1.04x slower                                                   |
| unpickle             | 14.1 us                                                | 15.1 us: 1.07x slower                                                   |
| pickle_dict          | 27.3 us                                                | 31.1 us: 1.14x slower                                                   |
| Geometric mean       | (ref)                                                  | 1.13x faster                                                            |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.0 ms: 1.41x faster                                                   |
| python_startup_no_site | 5.82 ms                                                | 6.88 ms: 1.18x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.09x faster                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 11.5 ms: 1.28x faster                                                   |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 153 us: 3.32x faster                                                    |
| generators               | 76.8 ms                                                | 28.9 ms: 2.66x faster                                                   |
| deltablue                | 7.42 ms                                                | 3.76 ms: 1.97x faster                                                   |
| asyncio_tcp              | 925 ms                                                 | 502 ms: 1.84x faster                                                    |
| richards_super           | 90.7 ms                                                | 52.7 ms: 1.72x faster                                                   |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.81 sec: 1.66x faster                                                  |
| logging_silent           | 175 ns                                                 | 106 ns: 1.65x faster                                                    |
| crypto_pyaes             | 118 ms                                                 | 73.0 ms: 1.62x faster                                                   |
| richards                 | 74.9 ms                                                | 46.3 ms: 1.62x faster                                                   |
| scimark_sor              | 197 ms                                                 | 123 ms: 1.60x faster                                                    |
| async_tree_none          | 717 ms                                                 | 451 ms: 1.59x faster                                                    |
| sqlglot_parse            | 2.06 ms                                                | 1.31 ms: 1.57x faster                                                   |
| raytrace                 | 464 ms                                                 | 295 ms: 1.57x faster                                                    |
| scimark_monte_carlo      | 108 ms                                                 | 71.0 ms: 1.53x faster                                                   |
| go                       | 229 ms                                                 | 150 ms: 1.53x faster                                                    |
| sqlglot_transpile        | 2.45 ms                                                | 1.63 ms: 1.50x faster                                                   |
| pickle_pure_python       | 455 us                                                 | 303 us: 1.50x faster                                                    |
| async_tree_memoization   | 854 ms                                                 | 573 ms: 1.49x faster                                                    |
| async_tree_io            | 1.77 sec                                               | 1.19 sec: 1.49x faster                                                  |
| coroutines               | 31.8 ms                                                | 22.0 ms: 1.45x faster                                                   |
| chaos                    | 106 ms                                                 | 73.5 ms: 1.45x faster                                                   |
| scimark_lu               | 163 ms                                                 | 113 ms: 1.44x faster                                                    |
| python_startup           | 14.2 ms                                                | 10.0 ms: 1.41x faster                                                   |
| nbody                    | 142 ms                                                 | 103 ms: 1.38x faster                                                    |
| json_dumps               | 13.5 ms                                                | 9.87 ms: 1.37x faster                                                   |
| spectral_norm            | 150 ms                                                 | 109 ms: 1.37x faster                                                    |
| tomli_loads              | 2.92 sec                                               | 2.15 sec: 1.36x faster                                                  |
| deepcopy_memo            | 52.3 us                                                | 38.7 us: 1.35x faster                                                   |
| pyflate                  | 673 ms                                                 | 498 ms: 1.35x faster                                                    |
| logging_simple           | 8.07 us                                                | 6.01 us: 1.34x faster                                                   |
| logging_format           | 8.91 us                                                | 6.67 us: 1.33x faster                                                   |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 718 ms: 1.32x faster                                                    |
| unpack_sequence          | 64.7 ns                                                | 49.0 ns: 1.32x faster                                                   |
| xml_etree_process        | 74.9 ms                                                | 57.4 ms: 1.31x faster                                                   |
| pycparser                | 1.50 sec                                               | 1.16 sec: 1.30x faster                                                  |
| unpickle_pure_python     | 300 us                                                 | 233 us: 1.29x faster                                                    |
| tornado_http             | 127 ms                                                 | 99.1 ms: 1.29x faster                                                   |
| mako                     | 14.8 ms                                                | 11.5 ms: 1.28x faster                                                   |
| sqlglot_normalize        | 135 ms                                                 | 106 ms: 1.28x faster                                                    |
| float                    | 111 ms                                                 | 86.8 ms: 1.27x faster                                                   |
| deepcopy                 | 442 us                                                 | 351 us: 1.26x faster                                                    |
| sqlglot_optimize         | 65.3 ms                                                | 53.7 ms: 1.22x faster                                                   |
| deepcopy_reduce          | 3.82 us                                                | 3.15 us: 1.21x faster                                                   |
| mypy2                    | 428 ms                                                 | 358 ms: 1.20x faster                                                    |
| regex_compile            | 177 ms                                                 | 149 ms: 1.19x faster                                                    |
| fannkuch                 | 486 ms                                                 | 410 ms: 1.18x faster                                                    |
| docutils                 | 3.17 sec                                               | 2.68 sec: 1.18x faster                                                  |
| scimark_fft              | 424 ms                                                 | 359 ms: 1.18x faster                                                    |
| json_loads               | 28.8 us                                                | 25.0 us: 1.15x faster                                                   |
| pprint_safe_repr         | 955 ms                                                 | 834 ms: 1.15x faster                                                    |
| json                     | 5.42 ms                                                | 4.78 ms: 1.13x faster                                                   |
| pprint_pformat           | 1.99 sec                                               | 1.75 sec: 1.13x faster                                                  |
| xml_etree_generate       | 94.2 ms                                                | 83.2 ms: 1.13x faster                                                   |
| bench_thread_pool        | 947 us                                                 | 838 us: 1.13x faster                                                    |
| hexiom                   | 9.53 ms                                                | 8.53 ms: 1.12x faster                                                   |
| create_gc_cycles         | 1.67 ms                                                | 1.50 ms: 1.11x faster                                                   |
| dulwich_log              | 75.9 ms                                                | 69.3 ms: 1.10x faster                                                   |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 5.02 ms: 1.09x faster                                                   |
| regex_dna                | 222 ms                                                 | 205 ms: 1.08x faster                                                    |
| nqueens                  | 100 ms                                                 | 92.4 ms: 1.08x faster                                                   |
| xml_etree_parse          | 163 ms                                                 | 151 ms: 1.08x faster                                                    |
| mdp                      | 2.82 sec                                               | 2.62 sec: 1.08x faster                                                  |
| regex_v8                 | 25.0 ms                                                | 23.4 ms: 1.07x faster                                                   |
| pathlib                  | 20.0 ms                                                | 18.7 ms: 1.07x faster                                                   |
| sqlite_synth             | 2.93 us                                                | 2.77 us: 1.06x faster                                                   |
| meteor_contest           | 115 ms                                                 | 110 ms: 1.05x faster                                                    |
| xml_etree_iterparse      | 111 ms                                                 | 107 ms: 1.04x faster                                                    |
| comprehensions           | 26.8 us                                                | 25.9 us: 1.03x faster                                                   |
| gc_traversal             | 3.84 ms                                                | 3.86 ms: 1.00x slower                                                   |
| pidigits                 | 190 ms                                                 | 195 ms: 1.03x slower                                                    |
| pickle                   | 10.3 us                                                | 10.6 us: 1.03x slower                                                   |
| pickle_list              | 4.56 us                                                | 4.72 us: 1.04x slower                                                   |
| regex_effbot             | 3.23 ms                                                | 3.40 ms: 1.05x slower                                                   |
| unpickle                 | 14.1 us                                                | 15.1 us: 1.07x slower                                                   |
| async_generators         | 425 ms                                                 | 458 ms: 1.08x slower                                                    |
| pickle_dict              | 27.3 us                                                | 31.1 us: 1.14x slower                                                   |
| python_startup_no_site   | 5.82 ms                                                | 6.88 ms: 1.18x slower                                                   |
| coverage                 | 72.8 ms                                                | 86.2 ms: 1.18x slower                                                   |
| telco                    | 6.54 ms                                                | 8.03 ms: 1.23x slower                                                   |
| Geometric mean           | (ref)                                                  | 1.26x faster                                                            |

Benchmark hidden because not significant (2): unpickle_list, bench_mp_pool
Ignored benchmarks (19) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.20x
- 95% likely to have a speedup of 1.18x
- 99% likely to have a speedup of 1.17x
