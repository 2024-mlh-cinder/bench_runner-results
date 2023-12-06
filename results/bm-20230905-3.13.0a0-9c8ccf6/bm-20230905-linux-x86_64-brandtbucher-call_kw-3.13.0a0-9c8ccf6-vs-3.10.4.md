
# Results vs. 3.10.4

- fork: brandtbucher
- ref: call_kw
- machine: linux-x86_64
- commit hash: 9c8ccf6
- commit date: 2023-09-05
- overall geometric mean: 1.30x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.24x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.63 sec: 1.20x faster                                         |
| tornado_http   | 127 ms                                                 | 95.3 ms: 1.34x faster                                          |
| Geometric mean | (ref)                                                  | 1.27x faster                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 92.3 ms: 1.53x faster                                          |
| float          | 111 ms                                                 | 79.1 ms: 1.40x faster                                          |
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                           |
| Geometric mean | (ref)                                                  | 1.29x faster                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 135 ms: 1.31x faster                                           |
| regex_v8       | 25.0 ms                                                | 24.6 ms: 1.02x faster                                          |
| regex_dna      | 222 ms                                                 | 220 ms: 1.01x faster                                           |
| regex_effbot   | 3.23 ms                                                | 3.74 ms: 1.16x slower                                          |
| Geometric mean | (ref)                                                  | 1.04x faster                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 294 us: 1.55x faster                                           |
| unpickle_pure_python | 300 us                                                 | 210 us: 1.43x faster                                           |
| json_dumps           | 13.5 ms                                                | 9.75 ms: 1.39x faster                                          |
| tomli_loads          | 2.92 sec                                               | 2.12 sec: 1.38x faster                                         |
| xml_etree_process    | 74.9 ms                                                | 56.4 ms: 1.33x faster                                          |
| xml_etree_generate   | 94.2 ms                                                | 81.3 ms: 1.16x faster                                          |
| json_loads           | 28.8 us                                                | 25.4 us: 1.14x faster                                          |
| xml_etree_iterparse  | 111 ms                                                 | 101 ms: 1.10x faster                                           |
| xml_etree_parse      | 163 ms                                                 | 151 ms: 1.08x faster                                           |
| pickle               | 10.3 us                                                | 10.5 us: 1.02x slower                                          |
| pickle_list          | 4.56 us                                                | 4.66 us: 1.02x slower                                          |
| unpickle             | 14.1 us                                                | 14.5 us: 1.02x slower                                          |
| unpickle_list        | 4.82 us                                                | 5.06 us: 1.05x slower                                          |
| pickle_dict          | 27.3 us                                                | 31.5 us: 1.15x slower                                          |
| Geometric mean       | (ref)                                                  | 1.15x faster                                                   |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 9.48 ms: 1.49x faster                                          |
| python_startup_no_site | 5.82 ms                                                | 6.97 ms: 1.20x slower                                          |
| Geometric mean         | (ref)                                                  | 1.12x faster                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 10.7 ms: 1.38x faster                                          |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 142 us: 3.60x faster                                           |
| generators               | 76.8 ms                                                | 29.0 ms: 2.65x faster                                          |
| deltablue                | 7.42 ms                                                | 3.26 ms: 2.28x faster                                          |
| asyncio_tcp              | 925 ms                                                 | 489 ms: 1.89x faster                                           |
| chaos                    | 106 ms                                                 | 58.7 ms: 1.81x faster                                          |
| crypto_pyaes             | 118 ms                                                 | 68.5 ms: 1.73x faster                                          |
| logging_silent           | 175 ns                                                 | 103 ns: 1.71x faster                                           |
| raytrace                 | 464 ms                                                 | 273 ms: 1.70x faster                                           |
| richards_super           | 90.7 ms                                                | 53.7 ms: 1.69x faster                                          |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.80 sec: 1.67x faster                                         |
| scimark_sor              | 197 ms                                                 | 118 ms: 1.67x faster                                           |
| go                       | 229 ms                                                 | 139 ms: 1.65x faster                                           |
| scimark_monte_carlo      | 108 ms                                                 | 65.8 ms: 1.65x faster                                          |
| sqlglot_parse            | 2.06 ms                                                | 1.25 ms: 1.64x faster                                          |
| async_tree_none          | 717 ms                                                 | 440 ms: 1.63x faster                                           |
| hexiom                   | 9.53 ms                                                | 5.97 ms: 1.60x faster                                          |
| richards                 | 74.9 ms                                                | 47.3 ms: 1.58x faster                                          |
| sqlglot_transpile        | 2.45 ms                                                | 1.56 ms: 1.57x faster                                          |
| pickle_pure_python       | 455 us                                                 | 294 us: 1.55x faster                                           |
| nbody                    | 142 ms                                                 | 92.3 ms: 1.53x faster                                          |
| async_tree_memoization   | 854 ms                                                 | 566 ms: 1.51x faster                                           |
| scimark_lu               | 163 ms                                                 | 109 ms: 1.50x faster                                           |
| python_startup           | 14.2 ms                                                | 9.48 ms: 1.49x faster                                          |
| pyflate                  | 673 ms                                                 | 452 ms: 1.49x faster                                           |
| async_tree_io            | 1.77 sec                                               | 1.19 sec: 1.49x faster                                         |
| coroutines               | 31.8 ms                                                | 22.1 ms: 1.44x faster                                          |
| unpack_sequence          | 64.7 ns                                                | 45.0 ns: 1.44x faster                                          |
| deepcopy_memo            | 52.3 us                                                | 36.6 us: 1.43x faster                                          |
| unpickle_pure_python     | 300 us                                                 | 210 us: 1.43x faster                                           |
| spectral_norm            | 150 ms                                                 | 106 ms: 1.42x faster                                           |
| float                    | 111 ms                                                 | 79.1 ms: 1.40x faster                                          |
| json_dumps               | 13.5 ms                                                | 9.75 ms: 1.39x faster                                          |
| tomli_loads              | 2.92 sec                                               | 2.12 sec: 1.38x faster                                         |
| mako                     | 14.8 ms                                                | 10.7 ms: 1.38x faster                                          |
| logging_format           | 8.91 us                                                | 6.51 us: 1.37x faster                                          |
| logging_simple           | 8.07 us                                                | 5.92 us: 1.36x faster                                          |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 704 ms: 1.35x faster                                           |
| pprint_pformat           | 1.99 sec                                               | 1.48 sec: 1.34x faster                                         |
| tornado_http             | 127 ms                                                 | 95.3 ms: 1.34x faster                                          |
| xml_etree_process        | 74.9 ms                                                | 56.4 ms: 1.33x faster                                          |
| pprint_safe_repr         | 955 ms                                                 | 724 ms: 1.32x faster                                           |
| sqlglot_normalize        | 135 ms                                                 | 103 ms: 1.32x faster                                           |
| regex_compile            | 177 ms                                                 | 135 ms: 1.31x faster                                           |
| fannkuch                 | 486 ms                                                 | 375 ms: 1.30x faster                                           |
| comprehensions           | 26.8 us                                                | 21.0 us: 1.28x faster                                          |
| deepcopy                 | 442 us                                                 | 346 us: 1.28x faster                                           |
| mypy2                    | 428 ms                                                 | 338 ms: 1.27x faster                                           |
| pycparser                | 1.50 sec                                               | 1.20 sec: 1.26x faster                                         |
| nqueens                  | 100 ms                                                 | 79.7 ms: 1.25x faster                                          |
| sqlglot_optimize         | 65.3 ms                                                | 52.2 ms: 1.25x faster                                          |
| deepcopy_reduce          | 3.82 us                                                | 3.08 us: 1.24x faster                                          |
| docutils                 | 3.17 sec                                               | 2.63 sec: 1.20x faster                                         |
| scimark_fft              | 424 ms                                                 | 356 ms: 1.19x faster                                           |
| bench_thread_pool        | 947 us                                                 | 811 us: 1.17x faster                                           |
| xml_etree_generate       | 94.2 ms                                                | 81.3 ms: 1.16x faster                                          |
| json_loads               | 28.8 us                                                | 25.4 us: 1.14x faster                                          |
| dulwich_log              | 75.9 ms                                                | 67.2 ms: 1.13x faster                                          |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.89 ms: 1.11x faster                                          |
| create_gc_cycles         | 1.67 ms                                                | 1.50 ms: 1.11x faster                                          |
| xml_etree_iterparse      | 111 ms                                                 | 101 ms: 1.10x faster                                           |
| mdp                      | 2.82 sec                                               | 2.57 sec: 1.10x faster                                         |
| json                     | 5.42 ms                                                | 4.96 ms: 1.09x faster                                          |
| meteor_contest           | 115 ms                                                 | 106 ms: 1.09x faster                                           |
| xml_etree_parse          | 163 ms                                                 | 151 ms: 1.08x faster                                           |
| sqlite_synth             | 2.93 us                                                | 2.73 us: 1.07x faster                                          |
| pathlib                  | 20.0 ms                                                | 18.8 ms: 1.06x faster                                          |
| regex_v8                 | 25.0 ms                                                | 24.6 ms: 1.02x faster                                          |
| pidigits                 | 190 ms                                                 | 188 ms: 1.01x faster                                           |
| regex_dna                | 222 ms                                                 | 220 ms: 1.01x faster                                           |
| bench_mp_pool            | 24.0 ms                                                | 24.0 ms: 1.00x slower                                          |
| pickle                   | 10.3 us                                                | 10.5 us: 1.02x slower                                          |
| pickle_list              | 4.56 us                                                | 4.66 us: 1.02x slower                                          |
| unpickle                 | 14.1 us                                                | 14.5 us: 1.02x slower                                          |
| unpickle_list            | 4.82 us                                                | 5.06 us: 1.05x slower                                          |
| async_generators         | 425 ms                                                 | 447 ms: 1.05x slower                                           |
| gc_traversal             | 3.84 ms                                                | 4.08 ms: 1.06x slower                                          |
| pickle_dict              | 27.3 us                                                | 31.5 us: 1.15x slower                                          |
| regex_effbot             | 3.23 ms                                                | 3.74 ms: 1.16x slower                                          |
| coverage                 | 72.8 ms                                                | 87.0 ms: 1.19x slower                                          |
| python_startup_no_site   | 5.82 ms                                                | 6.97 ms: 1.20x slower                                          |
| telco                    | 6.54 ms                                                | 7.96 ms: 1.22x slower                                          |
| dask                     | 423 ms                                                 | 519 ms: 1.23x slower                                           |
| Geometric mean           | (ref)                                                  | 1.30x faster                                                   |
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.28x
- 95% likely to have a speedup of 1.27x
- 99% likely to have a speedup of 1.24x
