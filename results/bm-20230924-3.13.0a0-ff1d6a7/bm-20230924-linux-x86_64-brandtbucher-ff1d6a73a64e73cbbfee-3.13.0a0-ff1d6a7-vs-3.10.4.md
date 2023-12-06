
# Results vs. 3.10.4

- fork: brandtbucher
- ref: ff1d6a73a64e73cbbfee
- machine: linux-x86_64
- commit hash: ff1d6a7
- commit date: 2023-09-24
- overall geometric mean: 1.28x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.22x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230924-linux-x86_64-brandtbucher-ff1d6a73a64e73cbbfee-3.13.0a0-ff1d6a7 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.69 sec: 1.18x faster                                                      |
| tornado_http   | 127 ms                                                 | 96.5 ms: 1.32x faster                                                       |
| Geometric mean | (ref)                                                  | 1.25x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230924-linux-x86_64-brandtbucher-ff1d6a73a64e73cbbfee-3.13.0a0-ff1d6a7 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 90.3 ms: 1.57x faster                                                       |
| float          | 111 ms                                                 | 82.5 ms: 1.34x faster                                                       |
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                                        |
| Geometric mean | (ref)                                                  | 1.28x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230924-linux-x86_64-brandtbucher-ff1d6a73a64e73cbbfee-3.13.0a0-ff1d6a7 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 140 ms: 1.26x faster                                                        |
| regex_dna      | 222 ms                                                 | 206 ms: 1.08x faster                                                        |
| regex_v8       | 25.0 ms                                                | 23.8 ms: 1.05x faster                                                       |
| regex_effbot   | 3.23 ms                                                | 3.49 ms: 1.08x slower                                                       |
| Geometric mean | (ref)                                                  | 1.07x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230924-linux-x86_64-brandtbucher-ff1d6a73a64e73cbbfee-3.13.0a0-ff1d6a7 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 300 us: 1.52x faster                                                        |
| tomli_loads          | 2.92 sec                                               | 2.00 sec: 1.46x faster                                                      |
| json_dumps           | 13.5 ms                                                | 9.90 ms: 1.37x faster                                                       |
| unpickle_pure_python | 300 us                                                 | 224 us: 1.34x faster                                                        |
| xml_etree_process    | 74.9 ms                                                | 58.4 ms: 1.28x faster                                                       |
| json_loads           | 28.8 us                                                | 25.5 us: 1.13x faster                                                       |
| xml_etree_generate   | 94.2 ms                                                | 84.5 ms: 1.11x faster                                                       |
| xml_etree_iterparse  | 111 ms                                                 | 103 ms: 1.09x faster                                                        |
| xml_etree_parse      | 163 ms                                                 | 152 ms: 1.07x faster                                                        |
| unpickle             | 14.1 us                                                | 14.2 us: 1.01x slower                                                       |
| unpickle_list        | 4.82 us                                                | 4.89 us: 1.02x slower                                                       |
| pickle               | 10.3 us                                                | 10.5 us: 1.02x slower                                                       |
| pickle_list          | 4.56 us                                                | 4.72 us: 1.03x slower                                                       |
| pickle_dict          | 27.3 us                                                | 31.1 us: 1.14x slower                                                       |
| Geometric mean       | (ref)                                                  | 1.14x faster                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230924-linux-x86_64-brandtbucher-ff1d6a73a64e73cbbfee-3.13.0a0-ff1d6a7 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.1 ms: 1.40x faster                                                       |
| python_startup_no_site | 5.82 ms                                                | 6.86 ms: 1.18x slower                                                       |
| Geometric mean         | (ref)                                                  | 1.09x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230924-linux-x86_64-brandtbucher-ff1d6a73a64e73cbbfee-3.13.0a0-ff1d6a7 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 10.9 ms: 1.35x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230924-linux-x86_64-brandtbucher-ff1d6a73a64e73cbbfee-3.13.0a0-ff1d6a7 |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 150 us: 3.41x faster                                                        |
| generators               | 76.8 ms                                                | 28.6 ms: 2.68x faster                                                       |
| deltablue                | 7.42 ms                                                | 3.39 ms: 2.19x faster                                                       |
| asyncio_tcp              | 925 ms                                                 | 485 ms: 1.91x faster                                                        |
| crypto_pyaes             | 118 ms                                                 | 70.0 ms: 1.69x faster                                                       |
| raytrace                 | 464 ms                                                 | 275 ms: 1.69x faster                                                        |
| chaos                    | 106 ms                                                 | 63.1 ms: 1.68x faster                                                       |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.79 sec: 1.67x faster                                                      |
| richards_super           | 90.7 ms                                                | 54.6 ms: 1.66x faster                                                       |
| logging_silent           | 175 ns                                                 | 108 ns: 1.62x faster                                                        |
| async_tree_none          | 717 ms                                                 | 446 ms: 1.61x faster                                                        |
| scimark_monte_carlo      | 108 ms                                                 | 67.5 ms: 1.60x faster                                                       |
| scimark_sor              | 197 ms                                                 | 123 ms: 1.60x faster                                                        |
| sqlglot_parse            | 2.06 ms                                                | 1.29 ms: 1.60x faster                                                       |
| go                       | 229 ms                                                 | 144 ms: 1.59x faster                                                        |
| nbody                    | 142 ms                                                 | 90.3 ms: 1.57x faster                                                       |
| richards                 | 74.9 ms                                                | 48.5 ms: 1.55x faster                                                       |
| sqlglot_transpile        | 2.45 ms                                                | 1.60 ms: 1.53x faster                                                       |
| pickle_pure_python       | 455 us                                                 | 300 us: 1.52x faster                                                        |
| async_tree_memoization   | 854 ms                                                 | 568 ms: 1.51x faster                                                        |
| pyflate                  | 673 ms                                                 | 457 ms: 1.47x faster                                                        |
| async_tree_io            | 1.77 sec                                               | 1.21 sec: 1.47x faster                                                      |
| tomli_loads              | 2.92 sec                                               | 2.00 sec: 1.46x faster                                                      |
| hexiom                   | 9.53 ms                                                | 6.57 ms: 1.45x faster                                                       |
| coroutines               | 31.8 ms                                                | 22.2 ms: 1.43x faster                                                       |
| scimark_lu               | 163 ms                                                 | 116 ms: 1.41x faster                                                        |
| python_startup           | 14.2 ms                                                | 10.1 ms: 1.40x faster                                                       |
| unpack_sequence          | 64.7 ns                                                | 46.9 ns: 1.38x faster                                                       |
| spectral_norm            | 150 ms                                                 | 109 ms: 1.37x faster                                                        |
| logging_format           | 8.91 us                                                | 6.48 us: 1.37x faster                                                       |
| json_dumps               | 13.5 ms                                                | 9.90 ms: 1.37x faster                                                       |
| logging_simple           | 8.07 us                                                | 5.91 us: 1.36x faster                                                       |
| deepcopy_memo            | 52.3 us                                                | 38.7 us: 1.35x faster                                                       |
| mako                     | 14.8 ms                                                | 10.9 ms: 1.35x faster                                                       |
| float                    | 111 ms                                                 | 82.5 ms: 1.34x faster                                                       |
| unpickle_pure_python     | 300 us                                                 | 224 us: 1.34x faster                                                        |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 713 ms: 1.33x faster                                                        |
| tornado_http             | 127 ms                                                 | 96.5 ms: 1.32x faster                                                       |
| pprint_pformat           | 1.99 sec                                               | 1.53 sec: 1.30x faster                                                      |
| pycparser                | 1.50 sec                                               | 1.16 sec: 1.30x faster                                                      |
| xml_etree_process        | 74.9 ms                                                | 58.4 ms: 1.28x faster                                                       |
| pprint_safe_repr         | 955 ms                                                 | 749 ms: 1.27x faster                                                        |
| scimark_fft              | 424 ms                                                 | 334 ms: 1.27x faster                                                        |
| regex_compile            | 177 ms                                                 | 140 ms: 1.26x faster                                                        |
| sqlglot_normalize        | 135 ms                                                 | 107 ms: 1.26x faster                                                        |
| deepcopy                 | 442 us                                                 | 358 us: 1.23x faster                                                        |
| mypy2                    | 428 ms                                                 | 347 ms: 1.23x faster                                                        |
| fannkuch                 | 486 ms                                                 | 397 ms: 1.23x faster                                                        |
| sqlglot_optimize         | 65.3 ms                                                | 53.9 ms: 1.21x faster                                                       |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.51 ms: 1.21x faster                                                       |
| docutils                 | 3.17 sec                                               | 2.69 sec: 1.18x faster                                                      |
| deepcopy_reduce          | 3.82 us                                                | 3.25 us: 1.17x faster                                                       |
| comprehensions           | 26.8 us                                                | 22.9 us: 1.17x faster                                                       |
| nqueens                  | 100 ms                                                 | 87.7 ms: 1.14x faster                                                       |
| bench_thread_pool        | 947 us                                                 | 832 us: 1.14x faster                                                        |
| json_loads               | 28.8 us                                                | 25.5 us: 1.13x faster                                                       |
| dulwich_log              | 75.9 ms                                                | 67.3 ms: 1.13x faster                                                       |
| create_gc_cycles         | 1.67 ms                                                | 1.50 ms: 1.11x faster                                                       |
| xml_etree_generate       | 94.2 ms                                                | 84.5 ms: 1.11x faster                                                       |
| json                     | 5.42 ms                                                | 4.89 ms: 1.11x faster                                                       |
| xml_etree_iterparse      | 111 ms                                                 | 103 ms: 1.09x faster                                                        |
| regex_dna                | 222 ms                                                 | 206 ms: 1.08x faster                                                        |
| pathlib                  | 20.0 ms                                                | 18.7 ms: 1.07x faster                                                       |
| xml_etree_parse          | 163 ms                                                 | 152 ms: 1.07x faster                                                        |
| sqlite_synth             | 2.93 us                                                | 2.75 us: 1.07x faster                                                       |
| regex_v8                 | 25.0 ms                                                | 23.8 ms: 1.05x faster                                                       |
| meteor_contest           | 115 ms                                                 | 109 ms: 1.05x faster                                                        |
| mdp                      | 2.82 sec                                               | 2.71 sec: 1.04x faster                                                      |
| pidigits                 | 190 ms                                                 | 188 ms: 1.01x faster                                                        |
| unpickle                 | 14.1 us                                                | 14.2 us: 1.01x slower                                                       |
| unpickle_list            | 4.82 us                                                | 4.89 us: 1.02x slower                                                       |
| pickle                   | 10.3 us                                                | 10.5 us: 1.02x slower                                                       |
| pickle_list              | 4.56 us                                                | 4.72 us: 1.03x slower                                                       |
| regex_effbot             | 3.23 ms                                                | 3.49 ms: 1.08x slower                                                       |
| async_generators         | 425 ms                                                 | 463 ms: 1.09x slower                                                        |
| gc_traversal             | 3.84 ms                                                | 4.20 ms: 1.09x slower                                                       |
| pickle_dict              | 27.3 us                                                | 31.1 us: 1.14x slower                                                       |
| coverage                 | 72.8 ms                                                | 85.4 ms: 1.17x slower                                                       |
| python_startup_no_site   | 5.82 ms                                                | 6.86 ms: 1.18x slower                                                       |
| telco                    | 6.54 ms                                                | 8.03 ms: 1.23x slower                                                       |
| dask                     | 423 ms                                                 | 530 ms: 1.26x slower                                                        |
| Geometric mean           | (ref)                                                  | 1.28x faster                                                                |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.26x
- 95% likely to have a speedup of 1.24x
- 99% likely to have a speedup of 1.22x
