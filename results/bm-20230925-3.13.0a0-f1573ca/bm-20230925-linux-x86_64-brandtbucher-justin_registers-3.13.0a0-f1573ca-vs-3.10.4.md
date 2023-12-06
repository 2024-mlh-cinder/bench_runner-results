
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: f1573ca
- commit date: 2023-09-25
- overall geometric mean: 1.24x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.13x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-f1573ca |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.70 sec: 1.17x faster                                                  |
| tornado_http   | 127 ms                                                 | 99.6 ms: 1.28x faster                                                   |
| Geometric mean | (ref)                                                  | 1.23x faster                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-f1573ca |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 111 ms: 1.28x faster                                                    |
| float          | 111 ms                                                 | 96.1 ms: 1.15x faster                                                   |
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                                    |
| Geometric mean | (ref)                                                  | 1.14x faster                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-f1573ca |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 154 ms: 1.15x faster                                                    |
| regex_dna      | 222 ms                                                 | 206 ms: 1.08x faster                                                    |
| regex_v8       | 25.0 ms                                                | 23.5 ms: 1.07x faster                                                   |
| regex_effbot   | 3.23 ms                                                | 3.45 ms: 1.07x slower                                                   |
| Geometric mean | (ref)                                                  | 1.05x faster                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-f1573ca |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 301 us: 1.51x faster                                                    |
| json_dumps           | 13.5 ms                                                | 9.84 ms: 1.38x faster                                                   |
| xml_etree_process    | 74.9 ms                                                | 58.2 ms: 1.29x faster                                                   |
| tomli_loads          | 2.92 sec                                               | 2.27 sec: 1.28x faster                                                  |
| unpickle_pure_python | 300 us                                                 | 238 us: 1.26x faster                                                    |
| json_loads           | 28.8 us                                                | 24.8 us: 1.16x faster                                                   |
| xml_etree_generate   | 94.2 ms                                                | 83.6 ms: 1.13x faster                                                   |
| xml_etree_parse      | 163 ms                                                 | 154 ms: 1.06x faster                                                    |
| xml_etree_iterparse  | 111 ms                                                 | 109 ms: 1.02x faster                                                    |
| unpickle_list        | 4.82 us                                                | 4.87 us: 1.01x slower                                                   |
| pickle               | 10.3 us                                                | 10.5 us: 1.02x slower                                                   |
| pickle_list          | 4.56 us                                                | 4.80 us: 1.05x slower                                                   |
| unpickle             | 14.1 us                                                | 15.2 us: 1.07x slower                                                   |
| pickle_dict          | 27.3 us                                                | 31.5 us: 1.16x slower                                                   |
| Geometric mean       | (ref)                                                  | 1.11x faster                                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-f1573ca |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.1 ms: 1.40x faster                                                   |
| python_startup_no_site | 5.82 ms                                                | 6.92 ms: 1.19x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.08x faster                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-f1573ca |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 11.8 ms: 1.25x faster                                                   |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-f1573ca |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 152 us: 3.36x faster                                                    |
| generators               | 76.8 ms                                                | 28.6 ms: 2.68x faster                                                   |
| asyncio_tcp              | 925 ms                                                 | 511 ms: 1.81x faster                                                    |
| deltablue                | 7.42 ms                                                | 4.26 ms: 1.74x faster                                                   |
| logging_silent           | 175 ns                                                 | 105 ns: 1.67x faster                                                    |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.82 sec: 1.65x faster                                                  |
| richards_super           | 90.7 ms                                                | 55.3 ms: 1.64x faster                                                   |
| crypto_pyaes             | 118 ms                                                 | 72.9 ms: 1.63x faster                                                   |
| scimark_sor              | 197 ms                                                 | 123 ms: 1.59x faster                                                    |
| async_tree_none          | 717 ms                                                 | 451 ms: 1.59x faster                                                    |
| sqlglot_parse            | 2.06 ms                                                | 1.32 ms: 1.56x faster                                                   |
| richards                 | 74.9 ms                                                | 48.5 ms: 1.55x faster                                                   |
| raytrace                 | 464 ms                                                 | 305 ms: 1.52x faster                                                    |
| pickle_pure_python       | 455 us                                                 | 301 us: 1.51x faster                                                    |
| go                       | 229 ms                                                 | 153 ms: 1.50x faster                                                    |
| sqlglot_transpile        | 2.45 ms                                                | 1.64 ms: 1.49x faster                                                   |
| async_tree_io            | 1.77 sec                                               | 1.20 sec: 1.47x faster                                                  |
| async_tree_memoization   | 854 ms                                                 | 584 ms: 1.46x faster                                                    |
| scimark_monte_carlo      | 108 ms                                                 | 74.1 ms: 1.46x faster                                                   |
| coroutines               | 31.8 ms                                                | 22.3 ms: 1.43x faster                                                   |
| scimark_lu               | 163 ms                                                 | 114 ms: 1.43x faster                                                    |
| python_startup           | 14.2 ms                                                | 10.1 ms: 1.40x faster                                                   |
| spectral_norm            | 150 ms                                                 | 108 ms: 1.39x faster                                                    |
| chaos                    | 106 ms                                                 | 76.5 ms: 1.39x faster                                                   |
| json_dumps               | 13.5 ms                                                | 9.84 ms: 1.38x faster                                                   |
| unpack_sequence          | 64.7 ns                                                | 48.6 ns: 1.33x faster                                                   |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 717 ms: 1.33x faster                                                    |
| logging_simple           | 8.07 us                                                | 6.09 us: 1.33x faster                                                   |
| logging_format           | 8.91 us                                                | 6.77 us: 1.32x faster                                                   |
| deepcopy_memo            | 52.3 us                                                | 40.0 us: 1.31x faster                                                   |
| xml_etree_process        | 74.9 ms                                                | 58.2 ms: 1.29x faster                                                   |
| tomli_loads              | 2.92 sec                                               | 2.27 sec: 1.28x faster                                                  |
| pycparser                | 1.50 sec                                               | 1.17 sec: 1.28x faster                                                  |
| nbody                    | 142 ms                                                 | 111 ms: 1.28x faster                                                    |
| tornado_http             | 127 ms                                                 | 99.6 ms: 1.28x faster                                                   |
| sqlglot_normalize        | 135 ms                                                 | 106 ms: 1.28x faster                                                    |
| pyflate                  | 673 ms                                                 | 533 ms: 1.26x faster                                                    |
| unpickle_pure_python     | 300 us                                                 | 238 us: 1.26x faster                                                    |
| mako                     | 14.8 ms                                                | 11.8 ms: 1.25x faster                                                   |
| deepcopy                 | 442 us                                                 | 355 us: 1.24x faster                                                    |
| sqlglot_optimize         | 65.3 ms                                                | 53.8 ms: 1.21x faster                                                   |
| deepcopy_reduce          | 3.82 us                                                | 3.16 us: 1.21x faster                                                   |
| mypy2                    | 428 ms                                                 | 358 ms: 1.20x faster                                                    |
| docutils                 | 3.17 sec                                               | 2.70 sec: 1.17x faster                                                  |
| json_loads               | 28.8 us                                                | 24.8 us: 1.16x faster                                                   |
| regex_compile            | 177 ms                                                 | 154 ms: 1.15x faster                                                    |
| float                    | 111 ms                                                 | 96.1 ms: 1.15x faster                                                   |
| scimark_fft              | 424 ms                                                 | 373 ms: 1.14x faster                                                    |
| json                     | 5.42 ms                                                | 4.80 ms: 1.13x faster                                                   |
| bench_thread_pool        | 947 us                                                 | 840 us: 1.13x faster                                                    |
| xml_etree_generate       | 94.2 ms                                                | 83.6 ms: 1.13x faster                                                   |
| dulwich_log              | 75.9 ms                                                | 68.5 ms: 1.11x faster                                                   |
| pprint_safe_repr         | 955 ms                                                 | 865 ms: 1.10x faster                                                    |
| create_gc_cycles         | 1.67 ms                                                | 1.51 ms: 1.10x faster                                                   |
| fannkuch                 | 486 ms                                                 | 442 ms: 1.10x faster                                                    |
| pprint_pformat           | 1.99 sec                                               | 1.82 sec: 1.09x faster                                                  |
| regex_dna                | 222 ms                                                 | 206 ms: 1.08x faster                                                    |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 5.09 ms: 1.07x faster                                                   |
| pathlib                  | 20.0 ms                                                | 18.7 ms: 1.07x faster                                                   |
| sqlite_synth             | 2.93 us                                                | 2.74 us: 1.07x faster                                                   |
| regex_v8                 | 25.0 ms                                                | 23.5 ms: 1.07x faster                                                   |
| xml_etree_parse          | 163 ms                                                 | 154 ms: 1.06x faster                                                    |
| meteor_contest           | 115 ms                                                 | 111 ms: 1.03x faster                                                    |
| nqueens                  | 100 ms                                                 | 97.2 ms: 1.03x faster                                                   |
| xml_etree_iterparse      | 111 ms                                                 | 109 ms: 1.02x faster                                                    |
| mdp                      | 2.82 sec                                               | 2.78 sec: 1.01x faster                                                  |
| pidigits                 | 190 ms                                                 | 188 ms: 1.01x faster                                                    |
| hexiom                   | 9.53 ms                                                | 9.45 ms: 1.01x faster                                                   |
| bench_mp_pool            | 24.0 ms                                                | 24.0 ms: 1.00x slower                                                   |
| unpickle_list            | 4.82 us                                                | 4.87 us: 1.01x slower                                                   |
| pickle                   | 10.3 us                                                | 10.5 us: 1.02x slower                                                   |
| pickle_list              | 4.56 us                                                | 4.80 us: 1.05x slower                                                   |
| regex_effbot             | 3.23 ms                                                | 3.45 ms: 1.07x slower                                                   |
| gc_traversal             | 3.84 ms                                                | 4.11 ms: 1.07x slower                                                   |
| unpickle                 | 14.1 us                                                | 15.2 us: 1.07x slower                                                   |
| async_generators         | 425 ms                                                 | 463 ms: 1.09x slower                                                    |
| pickle_dict              | 27.3 us                                                | 31.5 us: 1.16x slower                                                   |
| python_startup_no_site   | 5.82 ms                                                | 6.92 ms: 1.19x slower                                                   |
| coverage                 | 72.8 ms                                                | 87.6 ms: 1.20x slower                                                   |
| telco                    | 6.54 ms                                                | 8.08 ms: 1.24x slower                                                   |
| Geometric mean           | (ref)                                                  | 1.24x faster                                                            |

Benchmark hidden because not significant (1): comprehensions
Ignored benchmarks (19) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.17x
- 95% likely to have a speedup of 1.16x
- 99% likely to have a speedup of 1.13x
