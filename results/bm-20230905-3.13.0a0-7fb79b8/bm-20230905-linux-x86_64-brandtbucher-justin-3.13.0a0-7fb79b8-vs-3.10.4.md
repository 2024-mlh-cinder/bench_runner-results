
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 7fb79b8
- commit date: 2023-09-05
- overall geometric mean: 1.26x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.17x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-linux-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.70 sec: 1.17x faster                                        |
| tornado_http   | 127 ms                                                 | 97.4 ms: 1.31x faster                                         |
| Geometric mean | (ref)                                                  | 1.24x faster                                                  |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-linux-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 100 ms: 1.41x faster                                          |
| float          | 111 ms                                                 | 83.9 ms: 1.32x faster                                         |
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                          |
| Geometric mean | (ref)                                                  | 1.23x faster                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-linux-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 146 ms: 1.21x faster                                          |
| regex_v8       | 25.0 ms                                                | 24.8 ms: 1.01x faster                                         |
| regex_dna      | 222 ms                                                 | 225 ms: 1.01x slower                                          |
| regex_effbot   | 3.23 ms                                                | 3.67 ms: 1.14x slower                                         |
| Geometric mean | (ref)                                                  | 1.02x faster                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-linux-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 301 us: 1.51x faster                                          |
| json_dumps           | 13.5 ms                                                | 9.94 ms: 1.36x faster                                         |
| xml_etree_process    | 74.9 ms                                                | 57.4 ms: 1.31x faster                                         |
| unpickle_pure_python | 300 us                                                 | 231 us: 1.30x faster                                          |
| tomli_loads          | 2.92 sec                                               | 2.29 sec: 1.27x faster                                        |
| json_loads           | 28.8 us                                                | 25.4 us: 1.14x faster                                         |
| xml_etree_generate   | 94.2 ms                                                | 83.3 ms: 1.13x faster                                         |
| xml_etree_iterparse  | 111 ms                                                 | 105 ms: 1.06x faster                                          |
| xml_etree_parse      | 163 ms                                                 | 154 ms: 1.06x faster                                          |
| unpickle             | 14.1 us                                                | 14.3 us: 1.01x slower                                         |
| unpickle_list        | 4.82 us                                                | 4.89 us: 1.01x slower                                         |
| pickle_list          | 4.56 us                                                | 4.63 us: 1.02x slower                                         |
| pickle               | 10.3 us                                                | 10.9 us: 1.06x slower                                         |
| pickle_dict          | 27.3 us                                                | 31.2 us: 1.14x slower                                         |
| Geometric mean       | (ref)                                                  | 1.12x faster                                                  |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-linux-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 9.50 ms: 1.49x faster                                         |
| python_startup_no_site | 5.82 ms                                                | 6.99 ms: 1.20x slower                                         |
| Geometric mean         | (ref)                                                  | 1.11x faster                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-linux-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 11.3 ms: 1.30x faster                                         |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-linux-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 152 us: 3.35x faster                                          |
| generators               | 76.8 ms                                                | 30.0 ms: 2.56x faster                                         |
| deltablue                | 7.42 ms                                                | 3.48 ms: 2.13x faster                                         |
| asyncio_tcp              | 925 ms                                                 | 493 ms: 1.88x faster                                          |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.81 sec: 1.66x faster                                        |
| crypto_pyaes             | 118 ms                                                 | 72.2 ms: 1.64x faster                                         |
| logging_silent           | 175 ns                                                 | 107 ns: 1.64x faster                                          |
| richards_super           | 90.7 ms                                                | 55.6 ms: 1.63x faster                                         |
| raytrace                 | 464 ms                                                 | 285 ms: 1.63x faster                                          |
| chaos                    | 106 ms                                                 | 66.0 ms: 1.61x faster                                         |
| async_tree_none          | 717 ms                                                 | 447 ms: 1.60x faster                                          |
| scimark_sor              | 197 ms                                                 | 123 ms: 1.59x faster                                          |
| scimark_monte_carlo      | 108 ms                                                 | 68.1 ms: 1.59x faster                                         |
| sqlglot_parse            | 2.06 ms                                                | 1.31 ms: 1.57x faster                                         |
| go                       | 229 ms                                                 | 150 ms: 1.53x faster                                          |
| pickle_pure_python       | 455 us                                                 | 301 us: 1.51x faster                                          |
| richards                 | 74.9 ms                                                | 49.6 ms: 1.51x faster                                         |
| sqlglot_transpile        | 2.45 ms                                                | 1.63 ms: 1.50x faster                                         |
| python_startup           | 14.2 ms                                                | 9.50 ms: 1.49x faster                                         |
| async_tree_memoization   | 854 ms                                                 | 576 ms: 1.48x faster                                          |
| async_tree_io            | 1.77 sec                                               | 1.21 sec: 1.47x faster                                        |
| scimark_lu               | 163 ms                                                 | 114 ms: 1.43x faster                                          |
| coroutines               | 31.8 ms                                                | 22.3 ms: 1.43x faster                                         |
| unpack_sequence          | 64.7 ns                                                | 45.8 ns: 1.41x faster                                         |
| nbody                    | 142 ms                                                 | 100 ms: 1.41x faster                                          |
| pyflate                  | 673 ms                                                 | 481 ms: 1.40x faster                                          |
| json_dumps               | 13.5 ms                                                | 9.94 ms: 1.36x faster                                         |
| logging_simple           | 8.07 us                                                | 5.93 us: 1.36x faster                                         |
| logging_format           | 8.91 us                                                | 6.60 us: 1.35x faster                                         |
| spectral_norm            | 150 ms                                                 | 112 ms: 1.34x faster                                          |
| hexiom                   | 9.53 ms                                                | 7.15 ms: 1.33x faster                                         |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 714 ms: 1.33x faster                                          |
| float                    | 111 ms                                                 | 83.9 ms: 1.32x faster                                         |
| tornado_http             | 127 ms                                                 | 97.4 ms: 1.31x faster                                         |
| deepcopy_memo            | 52.3 us                                                | 40.0 us: 1.31x faster                                         |
| xml_etree_process        | 74.9 ms                                                | 57.4 ms: 1.31x faster                                         |
| mako                     | 14.8 ms                                                | 11.3 ms: 1.30x faster                                         |
| unpickle_pure_python     | 300 us                                                 | 231 us: 1.30x faster                                          |
| pprint_pformat           | 1.99 sec                                               | 1.54 sec: 1.29x faster                                        |
| tomli_loads              | 2.92 sec                                               | 2.29 sec: 1.27x faster                                        |
| pprint_safe_repr         | 955 ms                                                 | 752 ms: 1.27x faster                                          |
| sqlglot_normalize        | 135 ms                                                 | 108 ms: 1.25x faster                                          |
| deepcopy                 | 442 us                                                 | 354 us: 1.25x faster                                          |
| deepcopy_reduce          | 3.82 us                                                | 3.12 us: 1.22x faster                                         |
| pycparser                | 1.50 sec                                               | 1.23 sec: 1.22x faster                                        |
| regex_compile            | 177 ms                                                 | 146 ms: 1.21x faster                                          |
| mypy2                    | 428 ms                                                 | 354 ms: 1.21x faster                                          |
| sqlglot_optimize         | 65.3 ms                                                | 54.4 ms: 1.20x faster                                         |
| docutils                 | 3.17 sec                                               | 2.70 sec: 1.17x faster                                        |
| json_loads               | 28.8 us                                                | 25.4 us: 1.14x faster                                         |
| fannkuch                 | 486 ms                                                 | 429 ms: 1.13x faster                                          |
| xml_etree_generate       | 94.2 ms                                                | 83.3 ms: 1.13x faster                                         |
| bench_thread_pool        | 947 us                                                 | 841 us: 1.13x faster                                          |
| scimark_fft              | 424 ms                                                 | 377 ms: 1.12x faster                                          |
| json                     | 5.42 ms                                                | 4.84 ms: 1.12x faster                                         |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.88 ms: 1.12x faster                                         |
| comprehensions           | 26.8 us                                                | 24.1 us: 1.11x faster                                         |
| dulwich_log              | 75.9 ms                                                | 68.6 ms: 1.11x faster                                         |
| create_gc_cycles         | 1.67 ms                                                | 1.52 ms: 1.10x faster                                         |
| xml_etree_iterparse      | 111 ms                                                 | 105 ms: 1.06x faster                                          |
| sqlite_synth             | 2.93 us                                                | 2.76 us: 1.06x faster                                         |
| nqueens                  | 100 ms                                                 | 94.2 ms: 1.06x faster                                         |
| pathlib                  | 20.0 ms                                                | 18.9 ms: 1.06x faster                                         |
| xml_etree_parse          | 163 ms                                                 | 154 ms: 1.06x faster                                          |
| mdp                      | 2.82 sec                                               | 2.76 sec: 1.02x faster                                        |
| meteor_contest           | 115 ms                                                 | 113 ms: 1.02x faster                                          |
| pidigits                 | 190 ms                                                 | 188 ms: 1.01x faster                                          |
| regex_v8                 | 25.0 ms                                                | 24.8 ms: 1.01x faster                                         |
| bench_mp_pool            | 24.0 ms                                                | 24.0 ms: 1.00x slower                                         |
| gc_traversal             | 3.84 ms                                                | 3.86 ms: 1.01x slower                                         |
| unpickle                 | 14.1 us                                                | 14.3 us: 1.01x slower                                         |
| regex_dna                | 222 ms                                                 | 225 ms: 1.01x slower                                          |
| unpickle_list            | 4.82 us                                                | 4.89 us: 1.01x slower                                         |
| pickle_list              | 4.56 us                                                | 4.63 us: 1.02x slower                                         |
| pickle                   | 10.3 us                                                | 10.9 us: 1.06x slower                                         |
| async_generators         | 425 ms                                                 | 469 ms: 1.10x slower                                          |
| regex_effbot             | 3.23 ms                                                | 3.67 ms: 1.14x slower                                         |
| pickle_dict              | 27.3 us                                                | 31.2 us: 1.14x slower                                         |
| coverage                 | 72.8 ms                                                | 86.6 ms: 1.19x slower                                         |
| python_startup_no_site   | 5.82 ms                                                | 6.99 ms: 1.20x slower                                         |
| telco                    | 6.54 ms                                                | 8.20 ms: 1.25x slower                                         |
| dask                     | 423 ms                                                 | 534 ms: 1.26x slower                                          |
| Geometric mean           | (ref)                                                  | 1.26x faster                                                  |
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.21x
- 95% likely to have a speedup of 1.20x
- 99% likely to have a speedup of 1.17x
