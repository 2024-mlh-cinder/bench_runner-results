
# Results vs. 3.10.4

- fork: python
- ref: c1e2f3b2f70b8a72ea7e
- machine: linux-x86_64
- commit hash: c1e2f3b
- commit date: 2023-08-31
- overall geometric mean: 1.30x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.22x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230831-linux-x86_64-python-c1e2f3b2f70b8a72ea7e-3.13.0a0-c1e2f3b |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.62 sec: 1.21x faster                                                |
| tornado_http   | 127 ms                                                 | 95.7 ms: 1.33x faster                                                 |
| Geometric mean | (ref)                                                  | 1.27x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230831-linux-x86_64-python-c1e2f3b2f70b8a72ea7e-3.13.0a0-c1e2f3b |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 91.1 ms: 1.55x faster                                                 |
| float          | 111 ms                                                 | 78.7 ms: 1.40x faster                                                 |
| pidigits       | 190 ms                                                 | 189 ms: 1.01x faster                                                  |
| Geometric mean | (ref)                                                  | 1.30x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230831-linux-x86_64-python-c1e2f3b2f70b8a72ea7e-3.13.0a0-c1e2f3b |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 136 ms: 1.30x faster                                                  |
| regex_dna      | 222 ms                                                 | 214 ms: 1.04x faster                                                  |
| regex_v8       | 25.0 ms                                                | 24.9 ms: 1.01x faster                                                 |
| regex_effbot   | 3.23 ms                                                | 3.60 ms: 1.11x slower                                                 |
| Geometric mean | (ref)                                                  | 1.05x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230831-linux-x86_64-python-c1e2f3b2f70b8a72ea7e-3.13.0a0-c1e2f3b |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 299 us: 1.52x faster                                                  |
| unpickle_pure_python | 300 us                                                 | 214 us: 1.40x faster                                                  |
| tomli_loads          | 2.92 sec                                               | 2.12 sec: 1.38x faster                                                |
| json_dumps           | 13.5 ms                                                | 9.96 ms: 1.36x faster                                                 |
| xml_etree_process    | 74.9 ms                                                | 57.5 ms: 1.30x faster                                                 |
| xml_etree_generate   | 94.2 ms                                                | 82.4 ms: 1.14x faster                                                 |
| json_loads           | 28.8 us                                                | 25.3 us: 1.14x faster                                                 |
| xml_etree_iterparse  | 111 ms                                                 | 102 ms: 1.09x faster                                                  |
| xml_etree_parse      | 163 ms                                                 | 154 ms: 1.06x faster                                                  |
| pickle_list          | 4.56 us                                                | 4.64 us: 1.02x slower                                                 |
| pickle               | 10.3 us                                                | 10.6 us: 1.03x slower                                                 |
| unpickle             | 14.1 us                                                | 14.6 us: 1.03x slower                                                 |
| unpickle_list        | 4.82 us                                                | 5.01 us: 1.04x slower                                                 |
| pickle_dict          | 27.3 us                                                | 31.9 us: 1.17x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.14x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230831-linux-x86_64-python-c1e2f3b2f70b8a72ea7e-3.13.0a0-c1e2f3b |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 9.52 ms: 1.49x faster                                                 |
| python_startup_no_site | 5.82 ms                                                | 6.97 ms: 1.20x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.11x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230831-linux-x86_64-python-c1e2f3b2f70b8a72ea7e-3.13.0a0-c1e2f3b |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 10.8 ms: 1.36x faster                                                 |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230831-linux-x86_64-python-c1e2f3b2f70b8a72ea7e-3.13.0a0-c1e2f3b |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 140 us: 3.64x faster                                                  |
| generators               | 76.8 ms                                                | 28.8 ms: 2.67x faster                                                 |
| deltablue                | 7.42 ms                                                | 3.26 ms: 2.28x faster                                                 |
| asyncio_tcp              | 925 ms                                                 | 490 ms: 1.89x faster                                                  |
| chaos                    | 106 ms                                                 | 60.3 ms: 1.76x faster                                                 |
| crypto_pyaes             | 118 ms                                                 | 68.6 ms: 1.73x faster                                                 |
| logging_silent           | 175 ns                                                 | 103 ns: 1.69x faster                                                  |
| raytrace                 | 464 ms                                                 | 275 ms: 1.69x faster                                                  |
| richards_super           | 90.7 ms                                                | 53.9 ms: 1.68x faster                                                 |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.80 sec: 1.67x faster                                                |
| go                       | 229 ms                                                 | 139 ms: 1.65x faster                                                  |
| scimark_monte_carlo      | 108 ms                                                 | 66.2 ms: 1.63x faster                                                 |
| async_tree_none          | 717 ms                                                 | 440 ms: 1.63x faster                                                  |
| scimark_sor              | 197 ms                                                 | 121 ms: 1.62x faster                                                  |
| sqlglot_parse            | 2.06 ms                                                | 1.28 ms: 1.61x faster                                                 |
| richards                 | 74.9 ms                                                | 47.2 ms: 1.59x faster                                                 |
| hexiom                   | 9.53 ms                                                | 6.01 ms: 1.58x faster                                                 |
| nbody                    | 142 ms                                                 | 91.1 ms: 1.55x faster                                                 |
| sqlglot_transpile        | 2.45 ms                                                | 1.58 ms: 1.54x faster                                                 |
| pickle_pure_python       | 455 us                                                 | 299 us: 1.52x faster                                                  |
| pyflate                  | 673 ms                                                 | 444 ms: 1.52x faster                                                  |
| async_tree_memoization   | 854 ms                                                 | 568 ms: 1.51x faster                                                  |
| async_tree_io            | 1.77 sec                                               | 1.19 sec: 1.49x faster                                                |
| python_startup           | 14.2 ms                                                | 9.52 ms: 1.49x faster                                                 |
| scimark_lu               | 163 ms                                                 | 112 ms: 1.46x faster                                                  |
| spectral_norm            | 150 ms                                                 | 103 ms: 1.46x faster                                                  |
| coroutines               | 31.8 ms                                                | 22.1 ms: 1.44x faster                                                 |
| float                    | 111 ms                                                 | 78.7 ms: 1.40x faster                                                 |
| unpickle_pure_python     | 300 us                                                 | 214 us: 1.40x faster                                                  |
| deepcopy_memo            | 52.3 us                                                | 37.7 us: 1.39x faster                                                 |
| tomli_loads              | 2.92 sec                                               | 2.12 sec: 1.38x faster                                                |
| logging_format           | 8.91 us                                                | 6.46 us: 1.38x faster                                                 |
| mako                     | 14.8 ms                                                | 10.8 ms: 1.36x faster                                                 |
| logging_simple           | 8.07 us                                                | 5.93 us: 1.36x faster                                                 |
| json_dumps               | 13.5 ms                                                | 9.96 ms: 1.36x faster                                                 |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 702 ms: 1.36x faster                                                  |
| tornado_http             | 127 ms                                                 | 95.7 ms: 1.33x faster                                                 |
| pprint_pformat           | 1.99 sec                                               | 1.51 sec: 1.32x faster                                                |
| xml_etree_process        | 74.9 ms                                                | 57.5 ms: 1.30x faster                                                 |
| regex_compile            | 177 ms                                                 | 136 ms: 1.30x faster                                                  |
| comprehensions           | 26.8 us                                                | 20.8 us: 1.29x faster                                                 |
| pprint_safe_repr         | 955 ms                                                 | 741 ms: 1.29x faster                                                  |
| pycparser                | 1.50 sec                                               | 1.17 sec: 1.29x faster                                                |
| sqlglot_normalize        | 135 ms                                                 | 106 ms: 1.28x faster                                                  |
| deepcopy                 | 442 us                                                 | 350 us: 1.26x faster                                                  |
| mypy2                    | 428 ms                                                 | 340 ms: 1.26x faster                                                  |
| unpack_sequence          | 64.7 ns                                                | 51.5 ns: 1.26x faster                                                 |
| nqueens                  | 100 ms                                                 | 80.4 ms: 1.24x faster                                                 |
| fannkuch                 | 486 ms                                                 | 396 ms: 1.23x faster                                                  |
| sqlglot_optimize         | 65.3 ms                                                | 53.3 ms: 1.23x faster                                                 |
| docutils                 | 3.17 sec                                               | 2.62 sec: 1.21x faster                                                |
| deepcopy_reduce          | 3.82 us                                                | 3.17 us: 1.21x faster                                                 |
| scimark_fft              | 424 ms                                                 | 352 ms: 1.20x faster                                                  |
| bench_thread_pool        | 947 us                                                 | 813 us: 1.17x faster                                                  |
| dulwich_log              | 75.9 ms                                                | 66.0 ms: 1.15x faster                                                 |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.74 ms: 1.15x faster                                                 |
| xml_etree_generate       | 94.2 ms                                                | 82.4 ms: 1.14x faster                                                 |
| json_loads               | 28.8 us                                                | 25.3 us: 1.14x faster                                                 |
| create_gc_cycles         | 1.67 ms                                                | 1.47 ms: 1.13x faster                                                 |
| json                     | 5.42 ms                                                | 4.91 ms: 1.10x faster                                                 |
| xml_etree_iterparse      | 111 ms                                                 | 102 ms: 1.09x faster                                                  |
| sqlite_synth             | 2.93 us                                                | 2.72 us: 1.08x faster                                                 |
| meteor_contest           | 115 ms                                                 | 107 ms: 1.08x faster                                                  |
| pathlib                  | 20.0 ms                                                | 18.6 ms: 1.08x faster                                                 |
| xml_etree_parse          | 163 ms                                                 | 154 ms: 1.06x faster                                                  |
| gc_traversal             | 3.84 ms                                                | 3.66 ms: 1.05x faster                                                 |
| regex_dna                | 222 ms                                                 | 214 ms: 1.04x faster                                                  |
| mdp                      | 2.82 sec                                               | 2.73 sec: 1.04x faster                                                |
| regex_v8                 | 25.0 ms                                                | 24.9 ms: 1.01x faster                                                 |
| pidigits                 | 190 ms                                                 | 189 ms: 1.01x faster                                                  |
| bench_mp_pool            | 24.0 ms                                                | 24.0 ms: 1.00x slower                                                 |
| pickle_list              | 4.56 us                                                | 4.64 us: 1.02x slower                                                 |
| pickle                   | 10.3 us                                                | 10.6 us: 1.03x slower                                                 |
| unpickle                 | 14.1 us                                                | 14.6 us: 1.03x slower                                                 |
| unpickle_list            | 4.82 us                                                | 5.01 us: 1.04x slower                                                 |
| async_generators         | 425 ms                                                 | 448 ms: 1.05x slower                                                  |
| regex_effbot             | 3.23 ms                                                | 3.60 ms: 1.11x slower                                                 |
| pickle_dict              | 27.3 us                                                | 31.9 us: 1.17x slower                                                 |
| coverage                 | 72.8 ms                                                | 86.9 ms: 1.19x slower                                                 |
| python_startup_no_site   | 5.82 ms                                                | 6.97 ms: 1.20x slower                                                 |
| telco                    | 6.54 ms                                                | 8.01 ms: 1.22x slower                                                 |
| dask                     | 423 ms                                                 | 524 ms: 1.24x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.30x faster                                                          |
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.27x
- 95% likely to have a speedup of 1.26x
- 99% likely to have a speedup of 1.22x
