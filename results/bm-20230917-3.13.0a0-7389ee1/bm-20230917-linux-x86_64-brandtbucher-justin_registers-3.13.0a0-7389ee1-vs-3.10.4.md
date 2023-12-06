
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: 7389ee1
- commit date: 2023-09-17
- overall geometric mean: 1.27x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.21x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230917-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7389ee1 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.68 sec: 1.18x faster                                                  |
| tornado_http   | 127 ms                                                 | 97.0 ms: 1.31x faster                                                   |
| Geometric mean | (ref)                                                  | 1.25x faster                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230917-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7389ee1 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 93.3 ms: 1.52x faster                                                   |
| float          | 111 ms                                                 | 82.8 ms: 1.33x faster                                                   |
| pidigits       | 190 ms                                                 | 187 ms: 1.01x faster                                                    |
| Geometric mean | (ref)                                                  | 1.27x faster                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230917-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7389ee1 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 144 ms: 1.23x faster                                                    |
| regex_dna      | 222 ms                                                 | 208 ms: 1.06x faster                                                    |
| regex_v8       | 25.0 ms                                                | 23.7 ms: 1.06x faster                                                   |
| regex_effbot   | 3.23 ms                                                | 3.46 ms: 1.07x slower                                                   |
| Geometric mean | (ref)                                                  | 1.07x faster                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230917-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7389ee1 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 299 us: 1.53x faster                                                    |
| tomli_loads          | 2.92 sec                                               | 2.05 sec: 1.42x faster                                                  |
| json_dumps           | 13.5 ms                                                | 9.94 ms: 1.36x faster                                                   |
| unpickle_pure_python | 300 us                                                 | 226 us: 1.33x faster                                                    |
| xml_etree_process    | 74.9 ms                                                | 57.9 ms: 1.29x faster                                                   |
| json_loads           | 28.8 us                                                | 25.4 us: 1.14x faster                                                   |
| xml_etree_generate   | 94.2 ms                                                | 84.0 ms: 1.12x faster                                                   |
| xml_etree_iterparse  | 111 ms                                                 | 103 ms: 1.08x faster                                                    |
| xml_etree_parse      | 163 ms                                                 | 154 ms: 1.06x faster                                                    |
| pickle               | 10.3 us                                                | 10.5 us: 1.02x slower                                                   |
| pickle_list          | 4.56 us                                                | 4.77 us: 1.05x slower                                                   |
| unpickle             | 14.1 us                                                | 15.3 us: 1.08x slower                                                   |
| pickle_dict          | 27.3 us                                                | 31.9 us: 1.17x slower                                                   |
| Geometric mean       | (ref)                                                  | 1.13x faster                                                            |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230917-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7389ee1 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.2 ms: 1.39x faster                                                   |
| python_startup_no_site | 5.82 ms                                                | 6.94 ms: 1.19x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.08x faster                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230917-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7389ee1 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 11.4 ms: 1.29x faster                                                   |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230917-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7389ee1 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 152 us: 3.35x faster                                                    |
| generators               | 76.8 ms                                                | 28.3 ms: 2.71x faster                                                   |
| deltablue                | 7.42 ms                                                | 3.40 ms: 2.18x faster                                                   |
| asyncio_tcp              | 925 ms                                                 | 505 ms: 1.83x faster                                                    |
| raytrace                 | 464 ms                                                 | 271 ms: 1.71x faster                                                    |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.81 sec: 1.66x faster                                                  |
| chaos                    | 106 ms                                                 | 64.2 ms: 1.66x faster                                                   |
| logging_silent           | 175 ns                                                 | 106 ns: 1.65x faster                                                    |
| crypto_pyaes             | 118 ms                                                 | 72.1 ms: 1.64x faster                                                   |
| richards_super           | 90.7 ms                                                | 55.4 ms: 1.64x faster                                                   |
| scimark_sor              | 197 ms                                                 | 121 ms: 1.62x faster                                                    |
| scimark_monte_carlo      | 108 ms                                                 | 67.6 ms: 1.60x faster                                                   |
| sqlglot_parse            | 2.06 ms                                                | 1.29 ms: 1.60x faster                                                   |
| async_tree_none          | 717 ms                                                 | 450 ms: 1.59x faster                                                    |
| go                       | 229 ms                                                 | 147 ms: 1.56x faster                                                    |
| richards                 | 74.9 ms                                                | 48.1 ms: 1.56x faster                                                   |
| pickle_pure_python       | 455 us                                                 | 299 us: 1.53x faster                                                    |
| sqlglot_transpile        | 2.45 ms                                                | 1.61 ms: 1.52x faster                                                   |
| nbody                    | 142 ms                                                 | 93.3 ms: 1.52x faster                                                   |
| async_tree_memoization   | 854 ms                                                 | 576 ms: 1.48x faster                                                    |
| pyflate                  | 673 ms                                                 | 457 ms: 1.47x faster                                                    |
| async_tree_io            | 1.77 sec                                               | 1.21 sec: 1.47x faster                                                  |
| scimark_lu               | 163 ms                                                 | 114 ms: 1.44x faster                                                    |
| tomli_loads              | 2.92 sec                                               | 2.05 sec: 1.42x faster                                                  |
| coroutines               | 31.8 ms                                                | 22.4 ms: 1.42x faster                                                   |
| python_startup           | 14.2 ms                                                | 10.2 ms: 1.39x faster                                                   |
| hexiom                   | 9.53 ms                                                | 6.96 ms: 1.37x faster                                                   |
| spectral_norm            | 150 ms                                                 | 110 ms: 1.37x faster                                                    |
| json_dumps               | 13.5 ms                                                | 9.94 ms: 1.36x faster                                                   |
| float                    | 111 ms                                                 | 82.8 ms: 1.33x faster                                                   |
| logging_simple           | 8.07 us                                                | 6.05 us: 1.33x faster                                                   |
| logging_format           | 8.91 us                                                | 6.68 us: 1.33x faster                                                   |
| deepcopy_memo            | 52.3 us                                                | 39.4 us: 1.33x faster                                                   |
| unpickle_pure_python     | 300 us                                                 | 226 us: 1.33x faster                                                    |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 717 ms: 1.33x faster                                                    |
| tornado_http             | 127 ms                                                 | 97.0 ms: 1.31x faster                                                   |
| xml_etree_process        | 74.9 ms                                                | 57.9 ms: 1.29x faster                                                   |
| mako                     | 14.8 ms                                                | 11.4 ms: 1.29x faster                                                   |
| pprint_pformat           | 1.99 sec                                               | 1.54 sec: 1.29x faster                                                  |
| sqlglot_normalize        | 135 ms                                                 | 106 ms: 1.27x faster                                                    |
| scimark_fft              | 424 ms                                                 | 333 ms: 1.27x faster                                                    |
| pprint_safe_repr         | 955 ms                                                 | 755 ms: 1.26x faster                                                    |
| unpack_sequence          | 64.7 ns                                                | 51.5 ns: 1.26x faster                                                   |
| deepcopy                 | 442 us                                                 | 353 us: 1.25x faster                                                    |
| pycparser                | 1.50 sec                                               | 1.20 sec: 1.25x faster                                                  |
| regex_compile            | 177 ms                                                 | 144 ms: 1.23x faster                                                    |
| mypy2                    | 428 ms                                                 | 351 ms: 1.22x faster                                                    |
| sqlglot_optimize         | 65.3 ms                                                | 53.6 ms: 1.22x faster                                                   |
| fannkuch                 | 486 ms                                                 | 400 ms: 1.21x faster                                                    |
| deepcopy_reduce          | 3.82 us                                                | 3.16 us: 1.21x faster                                                   |
| docutils                 | 3.17 sec                                               | 2.68 sec: 1.18x faster                                                  |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.63 ms: 1.18x faster                                                   |
| bench_thread_pool        | 947 us                                                 | 833 us: 1.14x faster                                                    |
| json_loads               | 28.8 us                                                | 25.4 us: 1.14x faster                                                   |
| comprehensions           | 26.8 us                                                | 23.8 us: 1.13x faster                                                   |
| nqueens                  | 100 ms                                                 | 88.8 ms: 1.13x faster                                                   |
| xml_etree_generate       | 94.2 ms                                                | 84.0 ms: 1.12x faster                                                   |
| json                     | 5.42 ms                                                | 4.85 ms: 1.12x faster                                                   |
| dulwich_log              | 75.9 ms                                                | 68.7 ms: 1.10x faster                                                   |
| create_gc_cycles         | 1.67 ms                                                | 1.53 ms: 1.09x faster                                                   |
| xml_etree_iterparse      | 111 ms                                                 | 103 ms: 1.08x faster                                                    |
| sqlite_synth             | 2.93 us                                                | 2.75 us: 1.07x faster                                                   |
| regex_dna                | 222 ms                                                 | 208 ms: 1.06x faster                                                    |
| meteor_contest           | 115 ms                                                 | 108 ms: 1.06x faster                                                    |
| pathlib                  | 20.0 ms                                                | 18.9 ms: 1.06x faster                                                   |
| xml_etree_parse          | 163 ms                                                 | 154 ms: 1.06x faster                                                    |
| regex_v8                 | 25.0 ms                                                | 23.7 ms: 1.06x faster                                                   |
| mdp                      | 2.82 sec                                               | 2.77 sec: 1.02x faster                                                  |
| pidigits                 | 190 ms                                                 | 187 ms: 1.01x faster                                                    |
| gc_traversal             | 3.84 ms                                                | 3.86 ms: 1.00x slower                                                   |
| pickle                   | 10.3 us                                                | 10.5 us: 1.02x slower                                                   |
| pickle_list              | 4.56 us                                                | 4.77 us: 1.05x slower                                                   |
| regex_effbot             | 3.23 ms                                                | 3.46 ms: 1.07x slower                                                   |
| unpickle                 | 14.1 us                                                | 15.3 us: 1.08x slower                                                   |
| async_generators         | 425 ms                                                 | 462 ms: 1.09x slower                                                    |
| pickle_dict              | 27.3 us                                                | 31.9 us: 1.17x slower                                                   |
| python_startup_no_site   | 5.82 ms                                                | 6.94 ms: 1.19x slower                                                   |
| coverage                 | 72.8 ms                                                | 87.1 ms: 1.20x slower                                                   |
| telco                    | 6.54 ms                                                | 8.25 ms: 1.26x slower                                                   |
| dask                     | 423 ms                                                 | 536 ms: 1.27x slower                                                    |
| Geometric mean           | (ref)                                                  | 1.27x faster                                                            |

Benchmark hidden because not significant (2): unpickle_list, bench_mp_pool
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.24x
- 95% likely to have a speedup of 1.23x
- 99% likely to have a speedup of 1.21x
