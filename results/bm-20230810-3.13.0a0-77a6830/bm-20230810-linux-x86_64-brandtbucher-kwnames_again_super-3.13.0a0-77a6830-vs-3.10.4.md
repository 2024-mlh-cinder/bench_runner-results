
# Results vs. 3.10.4

- fork: brandtbucher
- ref: kwnames_again_super
- machine: linux-x86_64
- commit hash: 77a6830
- commit date: 2023-08-10
- overall geometric mean: 1.24x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.17x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again_super-3.13.0a0-77a6830 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.74 sec: 1.16x faster                                                     |
| tornado_http   | 127 ms                                                 | 104 ms: 1.23x faster                                                       |
| Geometric mean | (ref)                                                  | 1.19x faster                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again_super-3.13.0a0-77a6830 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 91.3 ms: 1.55x faster                                                      |
| float          | 111 ms                                                 | 84.5 ms: 1.31x faster                                                      |
| pidigits       | 190 ms                                                 | 189 ms: 1.00x faster                                                       |
| Geometric mean | (ref)                                                  | 1.27x faster                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again_super-3.13.0a0-77a6830 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 149 ms: 1.19x faster                                                       |
| regex_dna      | 222 ms                                                 | 211 ms: 1.05x faster                                                       |
| regex_effbot   | 3.23 ms                                                | 3.61 ms: 1.12x slower                                                      |
| Geometric mean | (ref)                                                  | 1.03x faster                                                               |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again_super-3.13.0a0-77a6830 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 321 us: 1.42x faster                                                       |
| json_dumps           | 13.5 ms                                                | 9.84 ms: 1.37x faster                                                      |
| unpickle_pure_python | 300 us                                                 | 228 us: 1.32x faster                                                       |
| tomli_loads          | 2.92 sec                                               | 2.25 sec: 1.30x faster                                                     |
| xml_etree_process    | 74.9 ms                                                | 60.0 ms: 1.25x faster                                                      |
| json_loads           | 28.8 us                                                | 25.6 us: 1.12x faster                                                      |
| xml_etree_generate   | 94.2 ms                                                | 85.0 ms: 1.11x faster                                                      |
| xml_etree_parse      | 163 ms                                                 | 152 ms: 1.07x faster                                                       |
| xml_etree_iterparse  | 111 ms                                                 | 105 ms: 1.07x faster                                                       |
| unpickle             | 14.1 us                                                | 14.6 us: 1.03x slower                                                      |
| unpickle_list        | 4.82 us                                                | 4.99 us: 1.03x slower                                                      |
| pickle_list          | 4.56 us                                                | 4.72 us: 1.04x slower                                                      |
| pickle               | 10.3 us                                                | 10.8 us: 1.05x slower                                                      |
| pickle_dict          | 27.3 us                                                | 33.3 us: 1.22x slower                                                      |
| Geometric mean       | (ref)                                                  | 1.11x faster                                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again_super-3.13.0a0-77a6830 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 9.46 ms: 1.50x faster                                                      |
| python_startup_no_site | 5.82 ms                                                | 6.90 ms: 1.19x slower                                                      |
| Geometric mean         | (ref)                                                  | 1.12x faster                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again_super-3.13.0a0-77a6830 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 11.4 ms: 1.30x faster                                                      |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again_super-3.13.0a0-77a6830 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 152 us: 3.36x faster                                                       |
| generators               | 76.8 ms                                                | 32.1 ms: 2.39x faster                                                      |
| deltablue                | 7.42 ms                                                | 3.77 ms: 1.97x faster                                                      |
| asyncio_tcp              | 925 ms                                                 | 496 ms: 1.86x faster                                                       |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.80 sec: 1.67x faster                                                     |
| chaos                    | 106 ms                                                 | 64.9 ms: 1.64x faster                                                      |
| crypto_pyaes             | 118 ms                                                 | 73.2 ms: 1.62x faster                                                      |
| logging_silent           | 175 ns                                                 | 109 ns: 1.60x faster                                                       |
| richards_super           | 90.7 ms                                                | 56.7 ms: 1.60x faster                                                      |
| async_tree_none          | 717 ms                                                 | 449 ms: 1.60x faster                                                       |
| raytrace                 | 464 ms                                                 | 291 ms: 1.59x faster                                                       |
| go                       | 229 ms                                                 | 147 ms: 1.56x faster                                                       |
| nbody                    | 142 ms                                                 | 91.3 ms: 1.55x faster                                                      |
| scimark_monte_carlo      | 108 ms                                                 | 69.8 ms: 1.55x faster                                                      |
| scimark_sor              | 197 ms                                                 | 130 ms: 1.51x faster                                                       |
| sqlglot_parse            | 2.06 ms                                                | 1.37 ms: 1.51x faster                                                      |
| python_startup           | 14.2 ms                                                | 9.46 ms: 1.50x faster                                                      |
| async_tree_io            | 1.77 sec                                               | 1.20 sec: 1.48x faster                                                     |
| richards                 | 74.9 ms                                                | 50.7 ms: 1.48x faster                                                      |
| async_tree_memoization   | 854 ms                                                 | 579 ms: 1.48x faster                                                       |
| hexiom                   | 9.53 ms                                                | 6.60 ms: 1.44x faster                                                      |
| pyflate                  | 673 ms                                                 | 468 ms: 1.44x faster                                                       |
| sqlglot_transpile        | 2.45 ms                                                | 1.70 ms: 1.44x faster                                                      |
| scimark_lu               | 163 ms                                                 | 114 ms: 1.43x faster                                                       |
| pickle_pure_python       | 455 us                                                 | 321 us: 1.42x faster                                                       |
| json_dumps               | 13.5 ms                                                | 9.84 ms: 1.37x faster                                                      |
| coroutines               | 31.8 ms                                                | 23.7 ms: 1.34x faster                                                      |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 714 ms: 1.33x faster                                                       |
| unpickle_pure_python     | 300 us                                                 | 228 us: 1.32x faster                                                       |
| deepcopy_memo            | 52.3 us                                                | 40.0 us: 1.31x faster                                                      |
| float                    | 111 ms                                                 | 84.5 ms: 1.31x faster                                                      |
| mako                     | 14.8 ms                                                | 11.4 ms: 1.30x faster                                                      |
| spectral_norm            | 150 ms                                                 | 115 ms: 1.30x faster                                                       |
| tomli_loads              | 2.92 sec                                               | 2.25 sec: 1.30x faster                                                     |
| pprint_pformat           | 1.99 sec                                               | 1.54 sec: 1.29x faster                                                     |
| unpack_sequence          | 64.7 ns                                                | 51.0 ns: 1.27x faster                                                      |
| pprint_safe_repr         | 955 ms                                                 | 756 ms: 1.26x faster                                                       |
| xml_etree_process        | 74.9 ms                                                | 60.0 ms: 1.25x faster                                                      |
| comprehensions           | 26.8 us                                                | 21.6 us: 1.24x faster                                                      |
| tornado_http             | 127 ms                                                 | 104 ms: 1.23x faster                                                       |
| pycparser                | 1.50 sec                                               | 1.24 sec: 1.21x faster                                                     |
| mypy2                    | 428 ms                                                 | 356 ms: 1.20x faster                                                       |
| sqlglot_normalize        | 135 ms                                                 | 113 ms: 1.20x faster                                                       |
| regex_compile            | 177 ms                                                 | 149 ms: 1.19x faster                                                       |
| nqueens                  | 100 ms                                                 | 84.3 ms: 1.19x faster                                                      |
| fannkuch                 | 486 ms                                                 | 410 ms: 1.19x faster                                                       |
| deepcopy                 | 442 us                                                 | 375 us: 1.18x faster                                                       |
| logging_simple           | 8.07 us                                                | 6.94 us: 1.16x faster                                                      |
| docutils                 | 3.17 sec                                               | 2.74 sec: 1.16x faster                                                     |
| sqlglot_optimize         | 65.3 ms                                                | 56.5 ms: 1.16x faster                                                      |
| logging_format           | 8.91 us                                                | 7.82 us: 1.14x faster                                                      |
| scimark_fft              | 424 ms                                                 | 372 ms: 1.14x faster                                                       |
| deepcopy_reduce          | 3.82 us                                                | 3.38 us: 1.13x faster                                                      |
| json_loads               | 28.8 us                                                | 25.6 us: 1.12x faster                                                      |
| bench_thread_pool        | 947 us                                                 | 844 us: 1.12x faster                                                       |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.92 ms: 1.11x faster                                                      |
| create_gc_cycles         | 1.67 ms                                                | 1.51 ms: 1.11x faster                                                      |
| xml_etree_generate       | 94.2 ms                                                | 85.0 ms: 1.11x faster                                                      |
| json                     | 5.42 ms                                                | 4.90 ms: 1.10x faster                                                      |
| pathlib                  | 20.0 ms                                                | 18.7 ms: 1.07x faster                                                      |
| xml_etree_parse          | 163 ms                                                 | 152 ms: 1.07x faster                                                       |
| meteor_contest           | 115 ms                                                 | 107 ms: 1.07x faster                                                       |
| xml_etree_iterparse      | 111 ms                                                 | 105 ms: 1.07x faster                                                       |
| regex_dna                | 222 ms                                                 | 211 ms: 1.05x faster                                                       |
| dulwich_log              | 75.9 ms                                                | 72.2 ms: 1.05x faster                                                      |
| mdp                      | 2.82 sec                                               | 2.69 sec: 1.05x faster                                                     |
| sqlite_synth             | 2.93 us                                                | 2.80 us: 1.05x faster                                                      |
| pidigits                 | 190 ms                                                 | 189 ms: 1.00x faster                                                       |
| gc_traversal             | 3.84 ms                                                | 3.84 ms: 1.00x faster                                                      |
| bench_mp_pool            | 24.0 ms                                                | 24.0 ms: 1.00x slower                                                      |
| unpickle                 | 14.1 us                                                | 14.6 us: 1.03x slower                                                      |
| unpickle_list            | 4.82 us                                                | 4.99 us: 1.03x slower                                                      |
| pickle_list              | 4.56 us                                                | 4.72 us: 1.04x slower                                                      |
| pickle                   | 10.3 us                                                | 10.8 us: 1.05x slower                                                      |
| async_generators         | 425 ms                                                 | 449 ms: 1.06x slower                                                       |
| regex_effbot             | 3.23 ms                                                | 3.61 ms: 1.12x slower                                                      |
| python_startup_no_site   | 5.82 ms                                                | 6.90 ms: 1.19x slower                                                      |
| coverage                 | 72.8 ms                                                | 86.9 ms: 1.19x slower                                                      |
| pickle_dict              | 27.3 us                                                | 33.3 us: 1.22x slower                                                      |
| telco                    | 6.54 ms                                                | 8.36 ms: 1.28x slower                                                      |
| dask                     | 423 ms                                                 | 554 ms: 1.31x slower                                                       |
| Geometric mean           | (ref)                                                  | 1.24x faster                                                               |

Benchmark hidden because not significant (1): regex_v8
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.19x
- 95% likely to have a speedup of 1.19x
- 99% likely to have a speedup of 1.17x
