
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: 5424850
- commit date: 2023-09-07
- overall geometric mean: 1.25x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.16x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230907-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-5424850 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.72 sec: 1.17x faster                                                  |
| tornado_http   | 127 ms                                                 | 98.0 ms: 1.30x faster                                                   |
| Geometric mean | (ref)                                                  | 1.23x faster                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230907-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-5424850 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 103 ms: 1.38x faster                                                    |
| float          | 111 ms                                                 | 82.9 ms: 1.33x faster                                                   |
| pidigits       | 190 ms                                                 | 187 ms: 1.01x faster                                                    |
| Geometric mean | (ref)                                                  | 1.23x faster                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230907-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-5424850 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 147 ms: 1.20x faster                                                    |
| regex_v8       | 25.0 ms                                                | 25.2 ms: 1.01x slower                                                   |
| regex_dna      | 222 ms                                                 | 226 ms: 1.02x slower                                                    |
| regex_effbot   | 3.23 ms                                                | 3.63 ms: 1.12x slower                                                   |
| Geometric mean | (ref)                                                  | 1.01x faster                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230907-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-5424850 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 303 us: 1.50x faster                                                    |
| json_dumps           | 13.5 ms                                                | 9.91 ms: 1.37x faster                                                   |
| tomli_loads          | 2.92 sec                                               | 2.26 sec: 1.29x faster                                                  |
| xml_etree_process    | 74.9 ms                                                | 58.3 ms: 1.29x faster                                                   |
| unpickle_pure_python | 300 us                                                 | 237 us: 1.27x faster                                                    |
| json_loads           | 28.8 us                                                | 25.3 us: 1.14x faster                                                   |
| xml_etree_generate   | 94.2 ms                                                | 84.5 ms: 1.11x faster                                                   |
| xml_etree_parse      | 163 ms                                                 | 152 ms: 1.07x faster                                                    |
| xml_etree_iterparse  | 111 ms                                                 | 105 ms: 1.07x faster                                                    |
| unpickle_list        | 4.82 us                                                | 4.93 us: 1.02x slower                                                   |
| unpickle             | 14.1 us                                                | 14.8 us: 1.04x slower                                                   |
| pickle               | 10.3 us                                                | 10.8 us: 1.05x slower                                                   |
| pickle_list          | 4.56 us                                                | 4.83 us: 1.06x slower                                                   |
| pickle_dict          | 27.3 us                                                | 32.2 us: 1.18x slower                                                   |
| Geometric mean       | (ref)                                                  | 1.11x faster                                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230907-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-5424850 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 9.59 ms: 1.48x faster                                                   |
| python_startup_no_site | 5.82 ms                                                | 7.06 ms: 1.21x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.10x faster                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230907-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-5424850 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 11.6 ms: 1.28x faster                                                   |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230907-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-5424850 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 158 us: 3.22x faster                                                    |
| generators               | 76.8 ms                                                | 30.0 ms: 2.56x faster                                                   |
| deltablue                | 7.42 ms                                                | 3.49 ms: 2.12x faster                                                   |
| asyncio_tcp              | 925 ms                                                 | 492 ms: 1.88x faster                                                    |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.81 sec: 1.66x faster                                                  |
| richards_super           | 90.7 ms                                                | 55.3 ms: 1.64x faster                                                   |
| raytrace                 | 464 ms                                                 | 283 ms: 1.64x faster                                                    |
| crypto_pyaes             | 118 ms                                                 | 72.7 ms: 1.63x faster                                                   |
| async_tree_none          | 717 ms                                                 | 445 ms: 1.61x faster                                                    |
| logging_silent           | 175 ns                                                 | 110 ns: 1.60x faster                                                    |
| sqlglot_parse            | 2.06 ms                                                | 1.30 ms: 1.58x faster                                                   |
| scimark_sor              | 197 ms                                                 | 125 ms: 1.58x faster                                                    |
| scimark_monte_carlo      | 108 ms                                                 | 68.7 ms: 1.58x faster                                                   |
| chaos                    | 106 ms                                                 | 67.5 ms: 1.58x faster                                                   |
| richards                 | 74.9 ms                                                | 49.6 ms: 1.51x faster                                                   |
| go                       | 229 ms                                                 | 152 ms: 1.51x faster                                                    |
| sqlglot_transpile        | 2.45 ms                                                | 1.62 ms: 1.51x faster                                                   |
| pickle_pure_python       | 455 us                                                 | 303 us: 1.50x faster                                                    |
| async_tree_memoization   | 854 ms                                                 | 573 ms: 1.49x faster                                                    |
| async_tree_io            | 1.77 sec                                               | 1.20 sec: 1.48x faster                                                  |
| python_startup           | 14.2 ms                                                | 9.59 ms: 1.48x faster                                                   |
| coroutines               | 31.8 ms                                                | 22.1 ms: 1.44x faster                                                   |
| scimark_lu               | 163 ms                                                 | 117 ms: 1.40x faster                                                    |
| pyflate                  | 673 ms                                                 | 482 ms: 1.40x faster                                                    |
| nbody                    | 142 ms                                                 | 103 ms: 1.38x faster                                                    |
| spectral_norm            | 150 ms                                                 | 110 ms: 1.37x faster                                                    |
| json_dumps               | 13.5 ms                                                | 9.91 ms: 1.37x faster                                                   |
| logging_format           | 8.91 us                                                | 6.62 us: 1.35x faster                                                   |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 709 ms: 1.34x faster                                                    |
| logging_simple           | 8.07 us                                                | 6.02 us: 1.34x faster                                                   |
| float                    | 111 ms                                                 | 82.9 ms: 1.33x faster                                                   |
| hexiom                   | 9.53 ms                                                | 7.29 ms: 1.31x faster                                                   |
| tornado_http             | 127 ms                                                 | 98.0 ms: 1.30x faster                                                   |
| tomli_loads              | 2.92 sec                                               | 2.26 sec: 1.29x faster                                                  |
| deepcopy_memo            | 52.3 us                                                | 40.7 us: 1.29x faster                                                   |
| xml_etree_process        | 74.9 ms                                                | 58.3 ms: 1.29x faster                                                   |
| pprint_pformat           | 1.99 sec                                               | 1.55 sec: 1.28x faster                                                  |
| mako                     | 14.8 ms                                                | 11.6 ms: 1.28x faster                                                   |
| unpickle_pure_python     | 300 us                                                 | 237 us: 1.27x faster                                                    |
| sqlglot_normalize        | 135 ms                                                 | 107 ms: 1.27x faster                                                    |
| pprint_safe_repr         | 955 ms                                                 | 756 ms: 1.26x faster                                                    |
| unpack_sequence          | 64.7 ns                                                | 51.5 ns: 1.26x faster                                                   |
| deepcopy                 | 442 us                                                 | 358 us: 1.23x faster                                                    |
| pycparser                | 1.50 sec                                               | 1.24 sec: 1.21x faster                                                  |
| sqlglot_optimize         | 65.3 ms                                                | 54.2 ms: 1.20x faster                                                   |
| deepcopy_reduce          | 3.82 us                                                | 3.18 us: 1.20x faster                                                   |
| mypy2                    | 428 ms                                                 | 357 ms: 1.20x faster                                                    |
| regex_compile            | 177 ms                                                 | 147 ms: 1.20x faster                                                    |
| docutils                 | 3.17 sec                                               | 2.72 sec: 1.17x faster                                                  |
| fannkuch                 | 486 ms                                                 | 426 ms: 1.14x faster                                                    |
| json_loads               | 28.8 us                                                | 25.3 us: 1.14x faster                                                   |
| scimark_fft              | 424 ms                                                 | 374 ms: 1.13x faster                                                    |
| bench_thread_pool        | 947 us                                                 | 844 us: 1.12x faster                                                    |
| create_gc_cycles         | 1.67 ms                                                | 1.49 ms: 1.12x faster                                                   |
| xml_etree_generate       | 94.2 ms                                                | 84.5 ms: 1.11x faster                                                   |
| json                     | 5.42 ms                                                | 4.86 ms: 1.11x faster                                                   |
| dulwich_log              | 75.9 ms                                                | 69.0 ms: 1.10x faster                                                   |
| xml_etree_parse          | 163 ms                                                 | 152 ms: 1.07x faster                                                    |
| comprehensions           | 26.8 us                                                | 25.1 us: 1.07x faster                                                   |
| xml_etree_iterparse      | 111 ms                                                 | 105 ms: 1.07x faster                                                    |
| sqlite_synth             | 2.93 us                                                | 2.76 us: 1.06x faster                                                   |
| pathlib                  | 20.0 ms                                                | 18.9 ms: 1.06x faster                                                   |
| nqueens                  | 100 ms                                                 | 94.9 ms: 1.05x faster                                                   |
| gc_traversal             | 3.84 ms                                                | 3.67 ms: 1.05x faster                                                   |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 5.25 ms: 1.04x faster                                                   |
| mdp                      | 2.82 sec                                               | 2.76 sec: 1.02x faster                                                  |
| meteor_contest           | 115 ms                                                 | 113 ms: 1.02x faster                                                    |
| pidigits                 | 190 ms                                                 | 187 ms: 1.01x faster                                                    |
| regex_v8                 | 25.0 ms                                                | 25.2 ms: 1.01x slower                                                   |
| regex_dna                | 222 ms                                                 | 226 ms: 1.02x slower                                                    |
| unpickle_list            | 4.82 us                                                | 4.93 us: 1.02x slower                                                   |
| unpickle                 | 14.1 us                                                | 14.8 us: 1.04x slower                                                   |
| pickle                   | 10.3 us                                                | 10.8 us: 1.05x slower                                                   |
| pickle_list              | 4.56 us                                                | 4.83 us: 1.06x slower                                                   |
| async_generators         | 425 ms                                                 | 471 ms: 1.11x slower                                                    |
| regex_effbot             | 3.23 ms                                                | 3.63 ms: 1.12x slower                                                   |
| pickle_dict              | 27.3 us                                                | 32.2 us: 1.18x slower                                                   |
| python_startup_no_site   | 5.82 ms                                                | 7.06 ms: 1.21x slower                                                   |
| coverage                 | 72.8 ms                                                | 88.9 ms: 1.22x slower                                                   |
| dask                     | 423 ms                                                 | 535 ms: 1.27x slower                                                    |
| telco                    | 6.54 ms                                                | 8.35 ms: 1.28x slower                                                   |
| Geometric mean           | (ref)                                                  | 1.25x faster                                                            |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.20x
- 95% likely to have a speedup of 1.19x
- 99% likely to have a speedup of 1.16x
