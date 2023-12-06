
# Results vs. 3.10.4

- fork: iritkatriel
- ref: refleak
- machine: linux-x86_64
- commit hash: 90d6409
- commit date: 2023-10-20
- overall geometric mean: 1.29x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.22x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1+-90d6409 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.65 sec: 1.20x faster                                         |
| tornado_http   | 127 ms                                                 | 95.5 ms: 1.33x faster                                          |
| Geometric mean | (ref)                                                  | 1.26x faster                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1+-90d6409 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 91.0 ms: 1.56x faster                                          |
| float          | 111 ms                                                 | 80.2 ms: 1.38x faster                                          |
| pidigits       | 190 ms                                                 | 187 ms: 1.01x faster                                           |
| Geometric mean | (ref)                                                  | 1.29x faster                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1+-90d6409 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 137 ms: 1.29x faster                                           |
| regex_dna      | 222 ms                                                 | 214 ms: 1.03x faster                                           |
| regex_v8       | 25.0 ms                                                | 25.4 ms: 1.01x slower                                          |
| regex_effbot   | 3.23 ms                                                | 3.52 ms: 1.09x slower                                          |
| Geometric mean | (ref)                                                  | 1.05x faster                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1+-90d6409 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 309 us: 1.47x faster                                           |
| tomli_loads          | 2.92 sec                                               | 2.12 sec: 1.38x faster                                         |
| unpickle_pure_python | 300 us                                                 | 220 us: 1.36x faster                                           |
| json_dumps           | 13.5 ms                                                | 10.4 ms: 1.31x faster                                          |
| xml_etree_process    | 74.9 ms                                                | 59.1 ms: 1.27x faster                                          |
| xml_etree_generate   | 94.2 ms                                                | 86.4 ms: 1.09x faster                                          |
| xml_etree_iterparse  | 111 ms                                                 | 105 ms: 1.06x faster                                           |
| json_loads           | 28.8 us                                                | 27.8 us: 1.04x faster                                          |
| xml_etree_parse      | 163 ms                                                 | 158 ms: 1.04x faster                                           |
| unpickle             | 14.1 us                                                | 14.6 us: 1.03x slower                                          |
| unpickle_list        | 4.82 us                                                | 5.18 us: 1.08x slower                                          |
| pickle               | 10.3 us                                                | 11.3 us: 1.10x slower                                          |
| pickle_list          | 4.56 us                                                | 5.16 us: 1.13x slower                                          |
| pickle_dict          | 27.3 us                                                | 35.3 us: 1.30x slower                                          |
| Geometric mean       | (ref)                                                  | 1.09x faster                                                   |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1+-90d6409 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.0 ms: 1.41x faster                                          |
| python_startup_no_site | 5.82 ms                                                | 6.85 ms: 1.18x slower                                          |
| Geometric mean         | (ref)                                                  | 1.09x faster                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1+-90d6409 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 11.6 ms: 1.28x faster                                          |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1+-90d6409 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 151 us: 3.38x faster                                           |
| generators               | 76.8 ms                                                | 29.7 ms: 2.59x faster                                          |
| deltablue                | 7.42 ms                                                | 3.36 ms: 2.21x faster                                          |
| asyncio_tcp              | 925 ms                                                 | 480 ms: 1.93x faster                                           |
| chaos                    | 106 ms                                                 | 61.3 ms: 1.73x faster                                          |
| raytrace                 | 464 ms                                                 | 273 ms: 1.70x faster                                           |
| richards_super           | 90.7 ms                                                | 53.7 ms: 1.69x faster                                          |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.78 sec: 1.69x faster                                         |
| crypto_pyaes             | 118 ms                                                 | 71.8 ms: 1.65x faster                                          |
| async_tree_none          | 717 ms                                                 | 439 ms: 1.63x faster                                           |
| logging_silent           | 175 ns                                                 | 108 ns: 1.62x faster                                           |
| comprehensions           | 26.8 us                                                | 16.6 us: 1.61x faster                                          |
| sqlglot_parse            | 2.06 ms                                                | 1.28 ms: 1.61x faster                                          |
| go                       | 229 ms                                                 | 144 ms: 1.59x faster                                           |
| scimark_monte_carlo      | 108 ms                                                 | 68.5 ms: 1.58x faster                                          |
| richards                 | 74.9 ms                                                | 47.5 ms: 1.58x faster                                          |
| hexiom                   | 9.53 ms                                                | 6.08 ms: 1.57x faster                                          |
| nbody                    | 142 ms                                                 | 91.0 ms: 1.56x faster                                          |
| scimark_sor              | 197 ms                                                 | 126 ms: 1.56x faster                                           |
| sqlglot_transpile        | 2.45 ms                                                | 1.60 ms: 1.52x faster                                          |
| async_tree_memoization   | 854 ms                                                 | 566 ms: 1.51x faster                                           |
| async_tree_io            | 1.77 sec                                               | 1.19 sec: 1.49x faster                                         |
| pyflate                  | 673 ms                                                 | 451 ms: 1.49x faster                                           |
| pickle_pure_python       | 455 us                                                 | 309 us: 1.47x faster                                           |
| unpack_sequence          | 64.7 ns                                                | 44.3 ns: 1.46x faster                                          |
| scimark_lu               | 163 ms                                                 | 115 ms: 1.42x faster                                           |
| python_startup           | 14.2 ms                                                | 10.0 ms: 1.41x faster                                          |
| coroutines               | 31.8 ms                                                | 22.9 ms: 1.39x faster                                          |
| logging_format           | 8.91 us                                                | 6.41 us: 1.39x faster                                          |
| float                    | 111 ms                                                 | 80.2 ms: 1.38x faster                                          |
| logging_simple           | 8.07 us                                                | 5.87 us: 1.38x faster                                          |
| tomli_loads              | 2.92 sec                                               | 2.12 sec: 1.38x faster                                         |
| spectral_norm            | 150 ms                                                 | 110 ms: 1.37x faster                                           |
| unpickle_pure_python     | 300 us                                                 | 220 us: 1.36x faster                                           |
| tornado_http             | 127 ms                                                 | 95.5 ms: 1.33x faster                                          |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 714 ms: 1.33x faster                                           |
| pprint_pformat           | 1.99 sec                                               | 1.50 sec: 1.32x faster                                         |
| deepcopy_memo            | 52.3 us                                                | 39.9 us: 1.31x faster                                          |
| json_dumps               | 13.5 ms                                                | 10.4 ms: 1.31x faster                                          |
| pprint_safe_repr         | 955 ms                                                 | 734 ms: 1.30x faster                                           |
| regex_compile            | 177 ms                                                 | 137 ms: 1.29x faster                                           |
| mako                     | 14.8 ms                                                | 11.6 ms: 1.28x faster                                          |
| sqlglot_normalize        | 135 ms                                                 | 106 ms: 1.27x faster                                           |
| nqueens                  | 100 ms                                                 | 78.6 ms: 1.27x faster                                          |
| xml_etree_process        | 74.9 ms                                                | 59.1 ms: 1.27x faster                                          |
| mypy2                    | 428 ms                                                 | 342 ms: 1.25x faster                                           |
| pycparser                | 1.50 sec                                               | 1.21 sec: 1.24x faster                                         |
| deepcopy                 | 442 us                                                 | 357 us: 1.24x faster                                           |
| sqlglot_optimize         | 65.3 ms                                                | 53.5 ms: 1.22x faster                                          |
| deepcopy_reduce          | 3.82 us                                                | 3.14 us: 1.22x faster                                          |
| docutils                 | 3.17 sec                                               | 2.65 sec: 1.20x faster                                         |
| fannkuch                 | 486 ms                                                 | 406 ms: 1.20x faster                                           |
| bench_thread_pool        | 947 us                                                 | 812 us: 1.17x faster                                           |
| scimark_fft              | 424 ms                                                 | 366 ms: 1.16x faster                                           |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.76 ms: 1.15x faster                                          |
| create_gc_cycles         | 1.67 ms                                                | 1.47 ms: 1.14x faster                                          |
| dulwich_log              | 75.9 ms                                                | 67.1 ms: 1.13x faster                                          |
| mdp                      | 2.82 sec                                               | 2.54 sec: 1.11x faster                                         |
| xml_etree_generate       | 94.2 ms                                                | 86.4 ms: 1.09x faster                                          |
| meteor_contest           | 115 ms                                                 | 106 ms: 1.09x faster                                           |
| pathlib                  | 20.0 ms                                                | 18.9 ms: 1.06x faster                                          |
| json                     | 5.42 ms                                                | 5.11 ms: 1.06x faster                                          |
| xml_etree_iterparse      | 111 ms                                                 | 105 ms: 1.06x faster                                           |
| sqlite_synth             | 2.93 us                                                | 2.81 us: 1.04x faster                                          |
| json_loads               | 28.8 us                                                | 27.8 us: 1.04x faster                                          |
| xml_etree_parse          | 163 ms                                                 | 158 ms: 1.04x faster                                           |
| regex_dna                | 222 ms                                                 | 214 ms: 1.03x faster                                           |
| pidigits                 | 190 ms                                                 | 187 ms: 1.01x faster                                           |
| bench_mp_pool            | 24.0 ms                                                | 24.0 ms: 1.00x slower                                          |
| gc_traversal             | 3.84 ms                                                | 3.87 ms: 1.01x slower                                          |
| regex_v8                 | 25.0 ms                                                | 25.4 ms: 1.01x slower                                          |
| unpickle                 | 14.1 us                                                | 14.6 us: 1.03x slower                                          |
| async_generators         | 425 ms                                                 | 454 ms: 1.07x slower                                           |
| unpickle_list            | 4.82 us                                                | 5.18 us: 1.08x slower                                          |
| regex_effbot             | 3.23 ms                                                | 3.52 ms: 1.09x slower                                          |
| pickle                   | 10.3 us                                                | 11.3 us: 1.10x slower                                          |
| pickle_list              | 4.56 us                                                | 5.16 us: 1.13x slower                                          |
| python_startup_no_site   | 5.82 ms                                                | 6.85 ms: 1.18x slower                                          |
| coverage                 | 72.8 ms                                                | 90.5 ms: 1.24x slower                                          |
| telco                    | 6.54 ms                                                | 8.35 ms: 1.28x slower                                          |
| pickle_dict              | 27.3 us                                                | 35.3 us: 1.30x slower                                          |
| Geometric mean           | (ref)                                                  | 1.29x faster                                                   |
Ignored benchmarks (19) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.26x
- 95% likely to have a speedup of 1.25x
- 99% likely to have a speedup of 1.22x
