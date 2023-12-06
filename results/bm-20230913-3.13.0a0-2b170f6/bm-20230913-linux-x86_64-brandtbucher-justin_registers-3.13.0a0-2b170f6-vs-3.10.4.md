
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: 2b170f6
- commit date: 2023-09-13
- overall geometric mean: 1.25x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.17x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-2b170f6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.69 sec: 1.18x faster                                                  |
| tornado_http   | 127 ms                                                 | 97.4 ms: 1.31x faster                                                   |
| Geometric mean | (ref)                                                  | 1.24x faster                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-2b170f6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| float          | 111 ms                                                 | 84.3 ms: 1.31x faster                                                   |
| nbody          | 142 ms                                                 | 127 ms: 1.12x faster                                                    |
| pidigits       | 190 ms                                                 | 189 ms: 1.00x faster                                                    |
| Geometric mean | (ref)                                                  | 1.14x faster                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-2b170f6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 148 ms: 1.19x faster                                                    |
| regex_dna      | 222 ms                                                 | 209 ms: 1.06x faster                                                    |
| regex_v8       | 25.0 ms                                                | 24.1 ms: 1.04x faster                                                   |
| regex_effbot   | 3.23 ms                                                | 3.57 ms: 1.11x slower                                                   |
| Geometric mean | (ref)                                                  | 1.04x faster                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-2b170f6 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 298 us: 1.53x faster                                                    |
| json_dumps           | 13.5 ms                                                | 9.96 ms: 1.36x faster                                                   |
| tomli_loads          | 2.92 sec                                               | 2.18 sec: 1.34x faster                                                  |
| xml_etree_process    | 74.9 ms                                                | 57.8 ms: 1.30x faster                                                   |
| unpickle_pure_python | 300 us                                                 | 234 us: 1.28x faster                                                    |
| json_loads           | 28.8 us                                                | 25.4 us: 1.14x faster                                                   |
| xml_etree_generate   | 94.2 ms                                                | 83.7 ms: 1.12x faster                                                   |
| xml_etree_iterparse  | 111 ms                                                 | 103 ms: 1.08x faster                                                    |
| xml_etree_parse      | 163 ms                                                 | 152 ms: 1.08x faster                                                    |
| pickle_list          | 4.56 us                                                | 4.67 us: 1.02x slower                                                   |
| unpickle_list        | 4.82 us                                                | 4.94 us: 1.02x slower                                                   |
| pickle               | 10.3 us                                                | 10.8 us: 1.05x slower                                                   |
| unpickle             | 14.1 us                                                | 15.5 us: 1.09x slower                                                   |
| pickle_dict          | 27.3 us                                                | 31.7 us: 1.16x slower                                                   |
| Geometric mean       | (ref)                                                  | 1.12x faster                                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-2b170f6 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.1 ms: 1.40x faster                                                   |
| python_startup_no_site | 5.82 ms                                                | 6.89 ms: 1.18x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.09x faster                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-2b170f6 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 11.7 ms: 1.26x faster                                                   |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-2b170f6 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 155 us: 3.29x faster                                                    |
| generators               | 76.8 ms                                                | 27.8 ms: 2.76x faster                                                   |
| deltablue                | 7.42 ms                                                | 3.48 ms: 2.13x faster                                                   |
| asyncio_tcp              | 925 ms                                                 | 490 ms: 1.89x faster                                                    |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.79 sec: 1.68x faster                                                  |
| raytrace                 | 464 ms                                                 | 277 ms: 1.68x faster                                                    |
| logging_silent           | 175 ns                                                 | 105 ns: 1.67x faster                                                    |
| richards_super           | 90.7 ms                                                | 55.4 ms: 1.64x faster                                                   |
| scimark_monte_carlo      | 108 ms                                                 | 67.5 ms: 1.60x faster                                                   |
| async_tree_none          | 717 ms                                                 | 450 ms: 1.59x faster                                                    |
| crypto_pyaes             | 118 ms                                                 | 74.7 ms: 1.59x faster                                                   |
| scimark_sor              | 197 ms                                                 | 124 ms: 1.58x faster                                                    |
| sqlglot_parse            | 2.06 ms                                                | 1.31 ms: 1.58x faster                                                   |
| richards                 | 74.9 ms                                                | 48.4 ms: 1.55x faster                                                   |
| pickle_pure_python       | 455 us                                                 | 298 us: 1.53x faster                                                    |
| go                       | 229 ms                                                 | 151 ms: 1.52x faster                                                    |
| sqlglot_transpile        | 2.45 ms                                                | 1.63 ms: 1.50x faster                                                   |
| async_tree_memoization   | 854 ms                                                 | 572 ms: 1.49x faster                                                    |
| async_tree_io            | 1.77 sec                                               | 1.21 sec: 1.47x faster                                                  |
| chaos                    | 106 ms                                                 | 72.7 ms: 1.46x faster                                                   |
| scimark_lu               | 163 ms                                                 | 113 ms: 1.44x faster                                                    |
| coroutines               | 31.8 ms                                                | 22.1 ms: 1.44x faster                                                   |
| pyflate                  | 673 ms                                                 | 477 ms: 1.41x faster                                                    |
| python_startup           | 14.2 ms                                                | 10.1 ms: 1.40x faster                                                   |
| json_dumps               | 13.5 ms                                                | 9.96 ms: 1.36x faster                                                   |
| spectral_norm            | 150 ms                                                 | 112 ms: 1.34x faster                                                    |
| tomli_loads              | 2.92 sec                                               | 2.18 sec: 1.34x faster                                                  |
| logging_simple           | 8.07 us                                                | 6.03 us: 1.34x faster                                                   |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 713 ms: 1.33x faster                                                    |
| logging_format           | 8.91 us                                                | 6.71 us: 1.33x faster                                                   |
| pprint_pformat           | 1.99 sec                                               | 1.51 sec: 1.31x faster                                                  |
| float                    | 111 ms                                                 | 84.3 ms: 1.31x faster                                                   |
| tornado_http             | 127 ms                                                 | 97.4 ms: 1.31x faster                                                   |
| hexiom                   | 9.53 ms                                                | 7.28 ms: 1.31x faster                                                   |
| deepcopy_memo            | 52.3 us                                                | 40.1 us: 1.31x faster                                                   |
| xml_etree_process        | 74.9 ms                                                | 57.8 ms: 1.30x faster                                                   |
| pprint_safe_repr         | 955 ms                                                 | 741 ms: 1.29x faster                                                    |
| unpickle_pure_python     | 300 us                                                 | 234 us: 1.28x faster                                                    |
| sqlglot_normalize        | 135 ms                                                 | 107 ms: 1.26x faster                                                    |
| mako                     | 14.8 ms                                                | 11.7 ms: 1.26x faster                                                   |
| pycparser                | 1.50 sec                                               | 1.21 sec: 1.24x faster                                                  |
| deepcopy                 | 442 us                                                 | 362 us: 1.22x faster                                                    |
| sqlglot_optimize         | 65.3 ms                                                | 53.8 ms: 1.21x faster                                                   |
| mypy2                    | 428 ms                                                 | 358 ms: 1.20x faster                                                    |
| regex_compile            | 177 ms                                                 | 148 ms: 1.19x faster                                                    |
| deepcopy_reduce          | 3.82 us                                                | 3.22 us: 1.19x faster                                                   |
| docutils                 | 3.17 sec                                               | 2.69 sec: 1.18x faster                                                  |
| unpack_sequence          | 64.7 ns                                                | 55.2 ns: 1.17x faster                                                   |
| json_loads               | 28.8 us                                                | 25.4 us: 1.14x faster                                                   |
| bench_thread_pool        | 947 us                                                 | 838 us: 1.13x faster                                                    |
| xml_etree_generate       | 94.2 ms                                                | 83.7 ms: 1.12x faster                                                   |
| json                     | 5.42 ms                                                | 4.82 ms: 1.12x faster                                                   |
| nbody                    | 142 ms                                                 | 127 ms: 1.12x faster                                                    |
| fannkuch                 | 486 ms                                                 | 435 ms: 1.12x faster                                                    |
| create_gc_cycles         | 1.67 ms                                                | 1.50 ms: 1.11x faster                                                   |
| dulwich_log              | 75.9 ms                                                | 69.0 ms: 1.10x faster                                                   |
| scimark_fft              | 424 ms                                                 | 386 ms: 1.10x faster                                                    |
| xml_etree_iterparse      | 111 ms                                                 | 103 ms: 1.08x faster                                                    |
| xml_etree_parse          | 163 ms                                                 | 152 ms: 1.08x faster                                                    |
| mdp                      | 2.82 sec                                               | 2.63 sec: 1.07x faster                                                  |
| regex_dna                | 222 ms                                                 | 209 ms: 1.06x faster                                                    |
| comprehensions           | 26.8 us                                                | 25.4 us: 1.06x faster                                                   |
| pathlib                  | 20.0 ms                                                | 19.0 ms: 1.05x faster                                                   |
| sqlite_synth             | 2.93 us                                                | 2.81 us: 1.05x faster                                                   |
| nqueens                  | 100 ms                                                 | 95.7 ms: 1.04x faster                                                   |
| gc_traversal             | 3.84 ms                                                | 3.69 ms: 1.04x faster                                                   |
| regex_v8                 | 25.0 ms                                                | 24.1 ms: 1.04x faster                                                   |
| meteor_contest           | 115 ms                                                 | 111 ms: 1.04x faster                                                    |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 5.38 ms: 1.01x faster                                                   |
| pidigits                 | 190 ms                                                 | 189 ms: 1.00x faster                                                    |
| pickle_list              | 4.56 us                                                | 4.67 us: 1.02x slower                                                   |
| unpickle_list            | 4.82 us                                                | 4.94 us: 1.02x slower                                                   |
| pickle                   | 10.3 us                                                | 10.8 us: 1.05x slower                                                   |
| unpickle                 | 14.1 us                                                | 15.5 us: 1.09x slower                                                   |
| async_generators         | 425 ms                                                 | 470 ms: 1.11x slower                                                    |
| regex_effbot             | 3.23 ms                                                | 3.57 ms: 1.11x slower                                                   |
| pickle_dict              | 27.3 us                                                | 31.7 us: 1.16x slower                                                   |
| python_startup_no_site   | 5.82 ms                                                | 6.89 ms: 1.18x slower                                                   |
| coverage                 | 72.8 ms                                                | 86.8 ms: 1.19x slower                                                   |
| telco                    | 6.54 ms                                                | 8.13 ms: 1.24x slower                                                   |
| dask                     | 423 ms                                                 | 535 ms: 1.27x slower                                                    |
| Geometric mean           | (ref)                                                  | 1.25x faster                                                            |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.21x
- 95% likely to have a speedup of 1.19x
- 99% likely to have a speedup of 1.17x
