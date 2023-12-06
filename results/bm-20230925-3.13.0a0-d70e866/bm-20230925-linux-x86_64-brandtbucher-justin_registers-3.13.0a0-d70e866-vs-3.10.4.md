
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: d70e866
- commit date: 2023-09-25
- overall geometric mean: 1.28x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.22x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-d70e866 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.66 sec: 1.19x faster                                                  |
| tornado_http   | 127 ms                                                 | 96.9 ms: 1.32x faster                                                   |
| Geometric mean | (ref)                                                  | 1.25x faster                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-d70e866 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 95.9 ms: 1.48x faster                                                   |
| float          | 111 ms                                                 | 82.3 ms: 1.34x faster                                                   |
| pidigits       | 190 ms                                                 | 187 ms: 1.01x faster                                                    |
| Geometric mean | (ref)                                                  | 1.26x faster                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-d70e866 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 144 ms: 1.23x faster                                                    |
| regex_dna      | 222 ms                                                 | 201 ms: 1.10x faster                                                    |
| regex_v8       | 25.0 ms                                                | 23.2 ms: 1.08x faster                                                   |
| regex_effbot   | 3.23 ms                                                | 3.45 ms: 1.07x slower                                                   |
| Geometric mean | (ref)                                                  | 1.08x faster                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-d70e866 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 297 us: 1.53x faster                                                    |
| tomli_loads          | 2.92 sec                                               | 2.02 sec: 1.44x faster                                                  |
| json_dumps           | 13.5 ms                                                | 9.91 ms: 1.37x faster                                                   |
| unpickle_pure_python | 300 us                                                 | 227 us: 1.32x faster                                                    |
| xml_etree_process    | 74.9 ms                                                | 57.3 ms: 1.31x faster                                                   |
| json_loads           | 28.8 us                                                | 25.1 us: 1.15x faster                                                   |
| xml_etree_generate   | 94.2 ms                                                | 83.3 ms: 1.13x faster                                                   |
| xml_etree_iterparse  | 111 ms                                                 | 103 ms: 1.09x faster                                                    |
| xml_etree_parse      | 163 ms                                                 | 153 ms: 1.07x faster                                                    |
| pickle               | 10.3 us                                                | 10.2 us: 1.01x faster                                                   |
| unpickle_list        | 4.82 us                                                | 4.88 us: 1.01x slower                                                   |
| pickle_list          | 4.56 us                                                | 4.66 us: 1.02x slower                                                   |
| unpickle             | 14.1 us                                                | 15.0 us: 1.06x slower                                                   |
| pickle_dict          | 27.3 us                                                | 31.2 us: 1.14x slower                                                   |
| Geometric mean       | (ref)                                                  | 1.14x faster                                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-d70e866 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.1 ms: 1.40x faster                                                   |
| python_startup_no_site | 5.82 ms                                                | 6.90 ms: 1.19x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.09x faster                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-d70e866 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 11.5 ms: 1.28x faster                                                   |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-d70e866 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 151 us: 3.37x faster                                                    |
| generators               | 76.8 ms                                                | 28.2 ms: 2.72x faster                                                   |
| deltablue                | 7.42 ms                                                | 3.41 ms: 2.18x faster                                                   |
| asyncio_tcp              | 925 ms                                                 | 498 ms: 1.86x faster                                                    |
| raytrace                 | 464 ms                                                 | 272 ms: 1.70x faster                                                    |
| logging_silent           | 175 ns                                                 | 104 ns: 1.68x faster                                                    |
| richards_super           | 90.7 ms                                                | 54.4 ms: 1.67x faster                                                   |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.81 sec: 1.66x faster                                                  |
| crypto_pyaes             | 118 ms                                                 | 71.5 ms: 1.66x faster                                                   |
| chaos                    | 106 ms                                                 | 65.3 ms: 1.63x faster                                                   |
| scimark_monte_carlo      | 108 ms                                                 | 67.0 ms: 1.62x faster                                                   |
| scimark_sor              | 197 ms                                                 | 122 ms: 1.62x faster                                                    |
| async_tree_none          | 717 ms                                                 | 448 ms: 1.60x faster                                                    |
| sqlglot_parse            | 2.06 ms                                                | 1.30 ms: 1.58x faster                                                   |
| richards                 | 74.9 ms                                                | 48.0 ms: 1.56x faster                                                   |
| go                       | 229 ms                                                 | 147 ms: 1.56x faster                                                    |
| pickle_pure_python       | 455 us                                                 | 297 us: 1.53x faster                                                    |
| sqlglot_transpile        | 2.45 ms                                                | 1.63 ms: 1.51x faster                                                   |
| async_tree_memoization   | 854 ms                                                 | 569 ms: 1.50x faster                                                    |
| async_tree_io            | 1.77 sec                                               | 1.19 sec: 1.49x faster                                                  |
| pyflate                  | 673 ms                                                 | 453 ms: 1.49x faster                                                    |
| nbody                    | 142 ms                                                 | 95.9 ms: 1.48x faster                                                   |
| tomli_loads              | 2.92 sec                                               | 2.02 sec: 1.44x faster                                                  |
| coroutines               | 31.8 ms                                                | 22.2 ms: 1.43x faster                                                   |
| scimark_lu               | 163 ms                                                 | 114 ms: 1.43x faster                                                    |
| python_startup           | 14.2 ms                                                | 10.1 ms: 1.40x faster                                                   |
| spectral_norm            | 150 ms                                                 | 108 ms: 1.39x faster                                                    |
| unpack_sequence          | 64.7 ns                                                | 47.2 ns: 1.37x faster                                                   |
| hexiom                   | 9.53 ms                                                | 6.95 ms: 1.37x faster                                                   |
| json_dumps               | 13.5 ms                                                | 9.91 ms: 1.37x faster                                                   |
| float                    | 111 ms                                                 | 82.3 ms: 1.34x faster                                                   |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 715 ms: 1.33x faster                                                    |
| logging_simple           | 8.07 us                                                | 6.08 us: 1.33x faster                                                   |
| deepcopy_memo            | 52.3 us                                                | 39.5 us: 1.33x faster                                                   |
| logging_format           | 8.91 us                                                | 6.73 us: 1.32x faster                                                   |
| unpickle_pure_python     | 300 us                                                 | 227 us: 1.32x faster                                                    |
| tornado_http             | 127 ms                                                 | 96.9 ms: 1.32x faster                                                   |
| pprint_pformat           | 1.99 sec                                               | 1.51 sec: 1.31x faster                                                  |
| xml_etree_process        | 74.9 ms                                                | 57.3 ms: 1.31x faster                                                   |
| pprint_safe_repr         | 955 ms                                                 | 740 ms: 1.29x faster                                                    |
| mako                     | 14.8 ms                                                | 11.5 ms: 1.28x faster                                                   |
| sqlglot_normalize        | 135 ms                                                 | 106 ms: 1.28x faster                                                    |
| scimark_fft              | 424 ms                                                 | 334 ms: 1.27x faster                                                    |
| pycparser                | 1.50 sec                                               | 1.20 sec: 1.25x faster                                                  |
| deepcopy                 | 442 us                                                 | 355 us: 1.24x faster                                                    |
| regex_compile            | 177 ms                                                 | 144 ms: 1.23x faster                                                    |
| fannkuch                 | 486 ms                                                 | 396 ms: 1.23x faster                                                    |
| sqlglot_optimize         | 65.3 ms                                                | 53.4 ms: 1.22x faster                                                   |
| mypy2                    | 428 ms                                                 | 352 ms: 1.22x faster                                                    |
| deepcopy_reduce          | 3.82 us                                                | 3.17 us: 1.20x faster                                                   |
| docutils                 | 3.17 sec                                               | 2.66 sec: 1.19x faster                                                  |
| json_loads               | 28.8 us                                                | 25.1 us: 1.15x faster                                                   |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.79 ms: 1.14x faster                                                   |
| xml_etree_generate       | 94.2 ms                                                | 83.3 ms: 1.13x faster                                                   |
| bench_thread_pool        | 947 us                                                 | 838 us: 1.13x faster                                                    |
| comprehensions           | 26.8 us                                                | 23.8 us: 1.13x faster                                                   |
| nqueens                  | 100 ms                                                 | 89.6 ms: 1.12x faster                                                   |
| dulwich_log              | 75.9 ms                                                | 68.6 ms: 1.11x faster                                                   |
| create_gc_cycles         | 1.67 ms                                                | 1.51 ms: 1.11x faster                                                   |
| json                     | 5.42 ms                                                | 4.91 ms: 1.10x faster                                                   |
| regex_dna                | 222 ms                                                 | 201 ms: 1.10x faster                                                    |
| mdp                      | 2.82 sec                                               | 2.57 sec: 1.10x faster                                                  |
| xml_etree_iterparse      | 111 ms                                                 | 103 ms: 1.09x faster                                                    |
| regex_v8                 | 25.0 ms                                                | 23.2 ms: 1.08x faster                                                   |
| sqlite_synth             | 2.93 us                                                | 2.73 us: 1.08x faster                                                   |
| xml_etree_parse          | 163 ms                                                 | 153 ms: 1.07x faster                                                    |
| pathlib                  | 20.0 ms                                                | 18.8 ms: 1.06x faster                                                   |
| meteor_contest           | 115 ms                                                 | 108 ms: 1.06x faster                                                    |
| pidigits                 | 190 ms                                                 | 187 ms: 1.01x faster                                                    |
| pickle                   | 10.3 us                                                | 10.2 us: 1.01x faster                                                   |
| unpickle_list            | 4.82 us                                                | 4.88 us: 1.01x slower                                                   |
| pickle_list              | 4.56 us                                                | 4.66 us: 1.02x slower                                                   |
| unpickle                 | 14.1 us                                                | 15.0 us: 1.06x slower                                                   |
| regex_effbot             | 3.23 ms                                                | 3.45 ms: 1.07x slower                                                   |
| gc_traversal             | 3.84 ms                                                | 4.11 ms: 1.07x slower                                                   |
| async_generators         | 425 ms                                                 | 460 ms: 1.08x slower                                                    |
| pickle_dict              | 27.3 us                                                | 31.2 us: 1.14x slower                                                   |
| coverage                 | 72.8 ms                                                | 86.3 ms: 1.19x slower                                                   |
| python_startup_no_site   | 5.82 ms                                                | 6.90 ms: 1.19x slower                                                   |
| telco                    | 6.54 ms                                                | 8.08 ms: 1.23x slower                                                   |
| dask                     | 423 ms                                                 | 534 ms: 1.26x slower                                                    |
| Geometric mean           | (ref)                                                  | 1.28x faster                                                            |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.24x
- 95% likely to have a speedup of 1.23x
- 99% likely to have a speedup of 1.22x
