
# Results vs. 3.10.4

- fork: brandtbucher
- ref: kwnames_frame
- machine: linux-x86_64
- commit hash: 7f16231
- commit date: 2023-08-11
- overall geometric mean: 1.29x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.22x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230811-linux-x86_64-brandtbucher-kwnames_frame-3.13.0a0-7f16231 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.63 sec: 1.20x faster                                               |
| tornado_http   | 127 ms                                                 | 96.2 ms: 1.32x faster                                                |
| Geometric mean | (ref)                                                  | 1.26x faster                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230811-linux-x86_64-brandtbucher-kwnames_frame-3.13.0a0-7f16231 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 93.9 ms: 1.51x faster                                                |
| float          | 111 ms                                                 | 80.2 ms: 1.38x faster                                                |
| pidigits       | 190 ms                                                 | 189 ms: 1.00x faster                                                 |
| Geometric mean | (ref)                                                  | 1.28x faster                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230811-linux-x86_64-brandtbucher-kwnames_frame-3.13.0a0-7f16231 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 137 ms: 1.29x faster                                                 |
| regex_dna      | 222 ms                                                 | 213 ms: 1.04x faster                                                 |
| regex_effbot   | 3.23 ms                                                | 3.55 ms: 1.10x slower                                                |
| Geometric mean | (ref)                                                  | 1.05x faster                                                         |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230811-linux-x86_64-brandtbucher-kwnames_frame-3.13.0a0-7f16231 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 303 us: 1.50x faster                                                 |
| unpickle_pure_python | 300 us                                                 | 216 us: 1.39x faster                                                 |
| json_dumps           | 13.5 ms                                                | 9.78 ms: 1.38x faster                                                |
| tomli_loads          | 2.92 sec                                               | 2.12 sec: 1.38x faster                                               |
| xml_etree_process    | 74.9 ms                                                | 57.9 ms: 1.29x faster                                                |
| json_loads           | 28.8 us                                                | 25.5 us: 1.13x faster                                                |
| xml_etree_generate   | 94.2 ms                                                | 84.6 ms: 1.11x faster                                                |
| xml_etree_iterparse  | 111 ms                                                 | 104 ms: 1.08x faster                                                 |
| xml_etree_parse      | 163 ms                                                 | 153 ms: 1.07x faster                                                 |
| pickle_list          | 4.56 us                                                | 4.38 us: 1.04x faster                                                |
| pickle               | 10.3 us                                                | 10.4 us: 1.01x slower                                                |
| unpickle_list        | 4.82 us                                                | 4.89 us: 1.02x slower                                                |
| unpickle             | 14.1 us                                                | 15.0 us: 1.06x slower                                                |
| pickle_dict          | 27.3 us                                                | 31.1 us: 1.14x slower                                                |
| Geometric mean       | (ref)                                                  | 1.14x faster                                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230811-linux-x86_64-brandtbucher-kwnames_frame-3.13.0a0-7f16231 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 9.42 ms: 1.50x faster                                                |
| python_startup_no_site | 5.82 ms                                                | 6.90 ms: 1.19x slower                                                |
| Geometric mean         | (ref)                                                  | 1.13x faster                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230811-linux-x86_64-brandtbucher-kwnames_frame-3.13.0a0-7f16231 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 10.8 ms: 1.36x faster                                                |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230811-linux-x86_64-brandtbucher-kwnames_frame-3.13.0a0-7f16231 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 143 us: 3.57x faster                                                 |
| generators               | 76.8 ms                                                | 29.3 ms: 2.62x faster                                                |
| deltablue                | 7.42 ms                                                | 3.32 ms: 2.24x faster                                                |
| asyncio_tcp              | 925 ms                                                 | 489 ms: 1.89x faster                                                 |
| chaos                    | 106 ms                                                 | 61.0 ms: 1.74x faster                                                |
| crypto_pyaes             | 118 ms                                                 | 70.2 ms: 1.69x faster                                                |
| raytrace                 | 464 ms                                                 | 276 ms: 1.68x faster                                                 |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.79 sec: 1.68x faster                                               |
| logging_silent           | 175 ns                                                 | 105 ns: 1.67x faster                                                 |
| richards_super           | 90.7 ms                                                | 54.8 ms: 1.66x faster                                                |
| go                       | 229 ms                                                 | 140 ms: 1.64x faster                                                 |
| scimark_monte_carlo      | 108 ms                                                 | 66.5 ms: 1.63x faster                                                |
| scimark_sor              | 197 ms                                                 | 122 ms: 1.62x faster                                                 |
| sqlglot_parse            | 2.06 ms                                                | 1.28 ms: 1.61x faster                                                |
| async_tree_none          | 717 ms                                                 | 448 ms: 1.60x faster                                                 |
| unpack_sequence          | 64.7 ns                                                | 40.6 ns: 1.59x faster                                                |
| richards                 | 74.9 ms                                                | 47.6 ms: 1.57x faster                                                |
| hexiom                   | 9.53 ms                                                | 6.07 ms: 1.57x faster                                                |
| sqlglot_transpile        | 2.45 ms                                                | 1.60 ms: 1.53x faster                                                |
| pyflate                  | 673 ms                                                 | 446 ms: 1.51x faster                                                 |
| nbody                    | 142 ms                                                 | 93.9 ms: 1.51x faster                                                |
| pickle_pure_python       | 455 us                                                 | 303 us: 1.50x faster                                                 |
| python_startup           | 14.2 ms                                                | 9.42 ms: 1.50x faster                                                |
| scimark_lu               | 163 ms                                                 | 110 ms: 1.49x faster                                                 |
| async_tree_memoization   | 854 ms                                                 | 580 ms: 1.47x faster                                                 |
| async_tree_io            | 1.77 sec                                               | 1.23 sec: 1.44x faster                                               |
| unpickle_pure_python     | 300 us                                                 | 216 us: 1.39x faster                                                 |
| deepcopy_memo            | 52.3 us                                                | 37.6 us: 1.39x faster                                                |
| json_dumps               | 13.5 ms                                                | 9.78 ms: 1.38x faster                                                |
| tomli_loads              | 2.92 sec                                               | 2.12 sec: 1.38x faster                                               |
| coroutines               | 31.8 ms                                                | 23.1 ms: 1.38x faster                                                |
| float                    | 111 ms                                                 | 80.2 ms: 1.38x faster                                                |
| mako                     | 14.8 ms                                                | 10.8 ms: 1.36x faster                                                |
| spectral_norm            | 150 ms                                                 | 110 ms: 1.36x faster                                                 |
| logging_format           | 8.91 us                                                | 6.56 us: 1.36x faster                                                |
| logging_simple           | 8.07 us                                                | 5.98 us: 1.35x faster                                                |
| pprint_pformat           | 1.99 sec                                               | 1.49 sec: 1.33x faster                                               |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 717 ms: 1.33x faster                                                 |
| tornado_http             | 127 ms                                                 | 96.2 ms: 1.32x faster                                                |
| pprint_safe_repr         | 955 ms                                                 | 729 ms: 1.31x faster                                                 |
| xml_etree_process        | 74.9 ms                                                | 57.9 ms: 1.29x faster                                                |
| regex_compile            | 177 ms                                                 | 137 ms: 1.29x faster                                                 |
| sqlglot_normalize        | 135 ms                                                 | 105 ms: 1.29x faster                                                 |
| pycparser                | 1.50 sec                                               | 1.17 sec: 1.29x faster                                               |
| comprehensions           | 26.8 us                                                | 21.1 us: 1.27x faster                                                |
| mypy2                    | 428 ms                                                 | 340 ms: 1.26x faster                                                 |
| deepcopy                 | 442 us                                                 | 354 us: 1.25x faster                                                 |
| sqlglot_optimize         | 65.3 ms                                                | 52.8 ms: 1.24x faster                                                |
| fannkuch                 | 486 ms                                                 | 394 ms: 1.23x faster                                                 |
| nqueens                  | 100 ms                                                 | 81.9 ms: 1.22x faster                                                |
| deepcopy_reduce          | 3.82 us                                                | 3.16 us: 1.21x faster                                                |
| docutils                 | 3.17 sec                                               | 2.63 sec: 1.20x faster                                               |
| scimark_fft              | 424 ms                                                 | 354 ms: 1.20x faster                                                 |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.58 ms: 1.19x faster                                                |
| bench_thread_pool        | 947 us                                                 | 825 us: 1.15x faster                                                 |
| dulwich_log              | 75.9 ms                                                | 66.5 ms: 1.14x faster                                                |
| json_loads               | 28.8 us                                                | 25.5 us: 1.13x faster                                                |
| create_gc_cycles         | 1.67 ms                                                | 1.49 ms: 1.12x faster                                                |
| xml_etree_generate       | 94.2 ms                                                | 84.6 ms: 1.11x faster                                                |
| mdp                      | 2.82 sec                                               | 2.55 sec: 1.11x faster                                               |
| json                     | 5.42 ms                                                | 4.91 ms: 1.10x faster                                                |
| meteor_contest           | 115 ms                                                 | 106 ms: 1.08x faster                                                 |
| xml_etree_iterparse      | 111 ms                                                 | 104 ms: 1.08x faster                                                 |
| sqlite_synth             | 2.93 us                                                | 2.74 us: 1.07x faster                                                |
| xml_etree_parse          | 163 ms                                                 | 153 ms: 1.07x faster                                                 |
| pathlib                  | 20.0 ms                                                | 19.0 ms: 1.06x faster                                                |
| pickle_list              | 4.56 us                                                | 4.38 us: 1.04x faster                                                |
| regex_dna                | 222 ms                                                 | 213 ms: 1.04x faster                                                 |
| pidigits                 | 190 ms                                                 | 189 ms: 1.00x faster                                                 |
| bench_mp_pool            | 24.0 ms                                                | 24.0 ms: 1.00x slower                                                |
| pickle                   | 10.3 us                                                | 10.4 us: 1.01x slower                                                |
| unpickle_list            | 4.82 us                                                | 4.89 us: 1.02x slower                                                |
| async_generators         | 425 ms                                                 | 443 ms: 1.04x slower                                                 |
| unpickle                 | 14.1 us                                                | 15.0 us: 1.06x slower                                                |
| regex_effbot             | 3.23 ms                                                | 3.55 ms: 1.10x slower                                                |
| gc_traversal             | 3.84 ms                                                | 4.33 ms: 1.13x slower                                                |
| pickle_dict              | 27.3 us                                                | 31.1 us: 1.14x slower                                                |
| coverage                 | 72.8 ms                                                | 86.0 ms: 1.18x slower                                                |
| python_startup_no_site   | 5.82 ms                                                | 6.90 ms: 1.19x slower                                                |
| telco                    | 6.54 ms                                                | 8.01 ms: 1.22x slower                                                |
| dask                     | 423 ms                                                 | 525 ms: 1.24x slower                                                 |
| Geometric mean           | (ref)                                                  | 1.29x faster                                                         |

Benchmark hidden because not significant (1): regex_v8
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.27x
- 95% likely to have a speedup of 1.25x
- 99% likely to have a speedup of 1.22x
