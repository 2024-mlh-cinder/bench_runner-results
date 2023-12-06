
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_elf
- machine: linux-x86_64
- commit hash: 1799b79
- commit date: 2023-10-02
- overall geometric mean: 1.26x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.17x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-linux-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.66 sec: 1.19x faster                                            |
| tornado_http   | 127 ms                                                 | 96.7 ms: 1.32x faster                                             |
| Geometric mean | (ref)                                                  | 1.25x faster                                                      |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-linux-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 105 ms: 1.34x faster                                              |
| float          | 111 ms                                                 | 84.0 ms: 1.32x faster                                             |
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                              |
| Geometric mean | (ref)                                                  | 1.21x faster                                                      |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-linux-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 143 ms: 1.24x faster                                              |
| regex_dna      | 222 ms                                                 | 210 ms: 1.06x faster                                              |
| regex_v8       | 25.0 ms                                                | 24.5 ms: 1.02x faster                                             |
| regex_effbot   | 3.23 ms                                                | 3.39 ms: 1.05x slower                                             |
| Geometric mean | (ref)                                                  | 1.06x faster                                                      |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-linux-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 297 us: 1.53x faster                                              |
| json_dumps           | 13.5 ms                                                | 9.94 ms: 1.36x faster                                             |
| unpickle_pure_python | 300 us                                                 | 225 us: 1.33x faster                                              |
| tomli_loads          | 2.92 sec                                               | 2.20 sec: 1.32x faster                                            |
| xml_etree_process    | 74.9 ms                                                | 57.7 ms: 1.30x faster                                             |
| xml_etree_generate   | 94.2 ms                                                | 83.9 ms: 1.12x faster                                             |
| json_loads           | 28.8 us                                                | 26.1 us: 1.10x faster                                             |
| xml_etree_parse      | 163 ms                                                 | 153 ms: 1.07x faster                                              |
| xml_etree_iterparse  | 111 ms                                                 | 105 ms: 1.06x faster                                              |
| unpickle_list        | 4.82 us                                                | 4.86 us: 1.01x slower                                             |
| pickle               | 10.3 us                                                | 10.4 us: 1.02x slower                                             |
| pickle_list          | 4.56 us                                                | 4.70 us: 1.03x slower                                             |
| unpickle             | 14.1 us                                                | 16.5 us: 1.17x slower                                             |
| pickle_dict          | 27.3 us                                                | 31.9 us: 1.17x slower                                             |
| Geometric mean       | (ref)                                                  | 1.12x faster                                                      |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-linux-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.1 ms: 1.40x faster                                             |
| python_startup_no_site | 5.82 ms                                                | 6.92 ms: 1.19x slower                                             |
| Geometric mean         | (ref)                                                  | 1.09x faster                                                      |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-linux-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 11.1 ms: 1.34x faster                                             |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-linux-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 148 us: 3.45x faster                                              |
| generators               | 76.8 ms                                                | 28.5 ms: 2.69x faster                                             |
| deltablue                | 7.42 ms                                                | 3.61 ms: 2.05x faster                                             |
| asyncio_tcp              | 925 ms                                                 | 509 ms: 1.82x faster                                              |
| logging_silent           | 175 ns                                                 | 101 ns: 1.73x faster                                              |
| richards_super           | 90.7 ms                                                | 53.3 ms: 1.70x faster                                             |
| crypto_pyaes             | 118 ms                                                 | 70.9 ms: 1.67x faster                                             |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.82 sec: 1.65x faster                                            |
| scimark_sor              | 197 ms                                                 | 121 ms: 1.63x faster                                              |
| sqlglot_parse            | 2.06 ms                                                | 1.27 ms: 1.62x faster                                             |
| raytrace                 | 464 ms                                                 | 289 ms: 1.61x faster                                              |
| async_tree_none          | 717 ms                                                 | 457 ms: 1.57x faster                                              |
| richards                 | 74.9 ms                                                | 48.0 ms: 1.56x faster                                             |
| go                       | 229 ms                                                 | 147 ms: 1.55x faster                                              |
| pickle_pure_python       | 455 us                                                 | 297 us: 1.53x faster                                              |
| sqlglot_transpile        | 2.45 ms                                                | 1.60 ms: 1.53x faster                                             |
| chaos                    | 106 ms                                                 | 70.5 ms: 1.51x faster                                             |
| scimark_monte_carlo      | 108 ms                                                 | 73.0 ms: 1.48x faster                                             |
| async_tree_io            | 1.77 sec                                               | 1.22 sec: 1.46x faster                                            |
| async_tree_memoization   | 854 ms                                                 | 589 ms: 1.45x faster                                              |
| spectral_norm            | 150 ms                                                 | 104 ms: 1.44x faster                                              |
| scimark_lu               | 163 ms                                                 | 115 ms: 1.42x faster                                              |
| coroutines               | 31.8 ms                                                | 22.6 ms: 1.41x faster                                             |
| python_startup           | 14.2 ms                                                | 10.1 ms: 1.40x faster                                             |
| json_dumps               | 13.5 ms                                                | 9.94 ms: 1.36x faster                                             |
| deepcopy_memo            | 52.3 us                                                | 38.9 us: 1.35x faster                                             |
| nbody                    | 142 ms                                                 | 105 ms: 1.34x faster                                              |
| pyflate                  | 673 ms                                                 | 502 ms: 1.34x faster                                              |
| logging_simple           | 8.07 us                                                | 6.04 us: 1.34x faster                                             |
| mako                     | 14.8 ms                                                | 11.1 ms: 1.34x faster                                             |
| unpickle_pure_python     | 300 us                                                 | 225 us: 1.33x faster                                              |
| logging_format           | 8.91 us                                                | 6.68 us: 1.33x faster                                             |
| tomli_loads              | 2.92 sec                                               | 2.20 sec: 1.32x faster                                            |
| tornado_http             | 127 ms                                                 | 96.7 ms: 1.32x faster                                             |
| float                    | 111 ms                                                 | 84.0 ms: 1.32x faster                                             |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 727 ms: 1.31x faster                                              |
| xml_etree_process        | 74.9 ms                                                | 57.7 ms: 1.30x faster                                             |
| sqlglot_normalize        | 135 ms                                                 | 107 ms: 1.27x faster                                              |
| deepcopy                 | 442 us                                                 | 349 us: 1.27x faster                                              |
| deepcopy_reduce          | 3.82 us                                                | 3.03 us: 1.26x faster                                             |
| unpack_sequence          | 64.7 ns                                                | 51.9 ns: 1.25x faster                                             |
| regex_compile            | 177 ms                                                 | 143 ms: 1.24x faster                                              |
| hexiom                   | 9.53 ms                                                | 7.71 ms: 1.23x faster                                             |
| mypy2                    | 428 ms                                                 | 349 ms: 1.23x faster                                              |
| pycparser                | 1.50 sec                                               | 1.22 sec: 1.23x faster                                            |
| sqlglot_optimize         | 65.3 ms                                                | 53.6 ms: 1.22x faster                                             |
| docutils                 | 3.17 sec                                               | 2.66 sec: 1.19x faster                                            |
| scimark_fft              | 424 ms                                                 | 357 ms: 1.19x faster                                              |
| fannkuch                 | 486 ms                                                 | 419 ms: 1.16x faster                                              |
| bench_thread_pool        | 947 us                                                 | 841 us: 1.13x faster                                              |
| xml_etree_generate       | 94.2 ms                                                | 83.9 ms: 1.12x faster                                             |
| dulwich_log              | 75.9 ms                                                | 67.9 ms: 1.12x faster                                             |
| pprint_safe_repr         | 955 ms                                                 | 855 ms: 1.12x faster                                              |
| pprint_pformat           | 1.99 sec                                               | 1.79 sec: 1.11x faster                                            |
| json_loads               | 28.8 us                                                | 26.1 us: 1.10x faster                                             |
| comprehensions           | 26.8 us                                                | 24.3 us: 1.10x faster                                             |
| json                     | 5.42 ms                                                | 4.91 ms: 1.10x faster                                             |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.95 ms: 1.10x faster                                             |
| create_gc_cycles         | 1.67 ms                                                | 1.54 ms: 1.08x faster                                             |
| sqlite_synth             | 2.93 us                                                | 2.73 us: 1.07x faster                                             |
| xml_etree_parse          | 163 ms                                                 | 153 ms: 1.07x faster                                              |
| mdp                      | 2.82 sec                                               | 2.65 sec: 1.06x faster                                            |
| xml_etree_iterparse      | 111 ms                                                 | 105 ms: 1.06x faster                                              |
| nqueens                  | 100 ms                                                 | 94.6 ms: 1.06x faster                                             |
| regex_dna                | 222 ms                                                 | 210 ms: 1.06x faster                                              |
| pathlib                  | 20.0 ms                                                | 19.1 ms: 1.05x faster                                             |
| meteor_contest           | 115 ms                                                 | 111 ms: 1.04x faster                                              |
| regex_v8                 | 25.0 ms                                                | 24.5 ms: 1.02x faster                                             |
| pidigits                 | 190 ms                                                 | 188 ms: 1.01x faster                                              |
| unpickle_list            | 4.82 us                                                | 4.86 us: 1.01x slower                                             |
| pickle                   | 10.3 us                                                | 10.4 us: 1.02x slower                                             |
| pickle_list              | 4.56 us                                                | 4.70 us: 1.03x slower                                             |
| regex_effbot             | 3.23 ms                                                | 3.39 ms: 1.05x slower                                             |
| async_generators         | 425 ms                                                 | 458 ms: 1.08x slower                                              |
| gc_traversal             | 3.84 ms                                                | 4.36 ms: 1.14x slower                                             |
| unpickle                 | 14.1 us                                                | 16.5 us: 1.17x slower                                             |
| pickle_dict              | 27.3 us                                                | 31.9 us: 1.17x slower                                             |
| coverage                 | 72.8 ms                                                | 85.3 ms: 1.17x slower                                             |
| python_startup_no_site   | 5.82 ms                                                | 6.92 ms: 1.19x slower                                             |
| telco                    | 6.54 ms                                                | 8.24 ms: 1.26x slower                                             |
| Geometric mean           | (ref)                                                  | 1.26x faster                                                      |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (19) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.21x
- 95% likely to have a speedup of 1.20x
- 99% likely to have a speedup of 1.17x
