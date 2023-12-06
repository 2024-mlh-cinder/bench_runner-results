
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 7bb54b5
- commit date: 2023-11-20
- overall geometric mean: 1.29x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.21x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 273 ms: 1.26x faster                                           |
| chameleon      | 9.84 ms                                                | 7.11 ms: 1.38x faster                                          |
| docutils       | 3.26 sec                                               | 2.66 sec: 1.23x faster                                         |
| tornado_http   | 131 ms                                                 | 96.5 ms: 1.35x faster                                          |
| Geometric mean | (ref)                                                  | 1.31x faster                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|-------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 443 ms: 1.65x faster                                           |
| async_tree_memoization  | 867 ms                                                 | 571 ms: 1.52x faster                                           |
| async_tree_io           | 1.79 sec                                               | 1.20 sec: 1.49x faster                                         |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 718 ms: 1.40x faster                                           |
| Geometric mean          | (ref)                                                  | 1.51x faster                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 100 ms: 1.48x faster                                           |
| float          | 116 ms                                                 | 85.0 ms: 1.37x faster                                          |
| pidigits       | 190 ms                                                 | 188 ms: 1.02x faster                                           |
| Geometric mean | (ref)                                                  | 1.27x faster                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 141 ms: 1.31x faster                                           |
| regex_v8       | 26.2 ms                                                | 24.3 ms: 1.08x faster                                          |
| regex_dna      | 215 ms                                                 | 216 ms: 1.00x slower                                           |
| regex_effbot   | 3.41 ms                                                | 3.63 ms: 1.07x slower                                          |
| Geometric mean | (ref)                                                  | 1.07x faster                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 309 us: 1.56x faster                                           |
| unpickle_pure_python | 327 us                                                 | 232 us: 1.41x faster                                           |
| tomli_loads          | 3.06 sec                                               | 2.21 sec: 1.39x faster                                         |
| json_dumps           | 14.3 ms                                                | 10.6 ms: 1.35x faster                                          |
| xml_etree_process    | 79.8 ms                                                | 61.0 ms: 1.31x faster                                          |
| xml_etree_generate   | 100.0 ms                                               | 89.1 ms: 1.12x faster                                          |
| json_loads           | 31.4 us                                                | 28.4 us: 1.11x faster                                          |
| xml_etree_parse      | 171 ms                                                 | 160 ms: 1.07x faster                                           |
| xml_etree_iterparse  | 116 ms                                                 | 110 ms: 1.06x faster                                           |
| pickle_list          | 5.05 us                                                | 4.89 us: 1.03x faster                                          |
| unpickle_list        | 5.10 us                                                | 5.28 us: 1.04x slower                                          |
| unpickle             | 14.9 us                                                | 15.5 us: 1.05x slower                                          |
| pickle               | 10.7 us                                                | 11.2 us: 1.05x slower                                          |
| pickle_dict          | 30.0 us                                                | 34.0 us: 1.14x slower                                          |
| Geometric mean       | (ref)                                                  | 1.14x faster                                                   |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.4 ms: 1.37x faster                                          |
| python_startup_no_site | 5.87 ms                                                | 9.10 ms: 1.55x slower                                          |
| Geometric mean         | (ref)                                                  | 1.06x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 12.4 ms: 1.31x faster                                          |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 120 us: 4.67x faster                                           |
| generators               | 78.9 ms                                                | 29.8 ms: 2.65x faster                                          |
| deltablue                | 7.81 ms                                                | 4.06 ms: 1.92x faster                                          |
| asyncio_tcp              | 918 ms                                                 | 489 ms: 1.88x faster                                           |
| richards_super           | 95.6 ms                                                | 52.0 ms: 1.84x faster                                          |
| raytrace                 | 498 ms                                                 | 286 ms: 1.74x faster                                           |
| chaos                    | 114 ms                                                 | 66.3 ms: 1.72x faster                                          |
| logging_silent           | 189 ns                                                 | 110 ns: 1.71x faster                                           |
| richards                 | 79.4 ms                                                | 46.8 ms: 1.70x faster                                          |
| scimark_sor              | 214 ms                                                 | 127 ms: 1.69x faster                                           |
| async_tree_none          | 732 ms                                                 | 443 ms: 1.65x faster                                           |
| sqlglot_parse            | 2.15 ms                                                | 1.32 ms: 1.62x faster                                          |
| crypto_pyaes             | 127 ms                                                 | 79.4 ms: 1.60x faster                                          |
| coroutines               | 34.5 ms                                                | 21.8 ms: 1.58x faster                                          |
| go                       | 238 ms                                                 | 152 ms: 1.57x faster                                           |
| scimark_monte_carlo      | 118 ms                                                 | 75.3 ms: 1.57x faster                                          |
| pickle_pure_python       | 482 us                                                 | 309 us: 1.56x faster                                           |
| sqlglot_transpile        | 2.55 ms                                                | 1.65 ms: 1.55x faster                                          |
| async_tree_memoization   | 867 ms                                                 | 571 ms: 1.52x faster                                           |
| async_tree_io            | 1.79 sec                                               | 1.20 sec: 1.49x faster                                         |
| nbody                    | 148 ms                                                 | 100 ms: 1.48x faster                                           |
| scimark_lu               | 175 ms                                                 | 119 ms: 1.48x faster                                           |
| comprehensions           | 28.5 us                                                | 19.3 us: 1.48x faster                                          |
| deepcopy_memo            | 58.8 us                                                | 40.4 us: 1.46x faster                                          |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.80 sec: 1.43x faster                                         |
| logging_simple           | 8.27 us                                                | 5.80 us: 1.43x faster                                          |
| logging_format           | 9.07 us                                                | 6.39 us: 1.42x faster                                          |
| pyflate                  | 708 ms                                                 | 502 ms: 1.41x faster                                           |
| unpickle_pure_python     | 327 us                                                 | 232 us: 1.41x faster                                           |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 718 ms: 1.40x faster                                           |
| unpack_sequence          | 65.7 ns                                                | 46.9 ns: 1.40x faster                                          |
| tomli_loads              | 3.06 sec                                               | 2.21 sec: 1.39x faster                                         |
| chameleon                | 9.84 ms                                                | 7.11 ms: 1.38x faster                                          |
| python_startup           | 14.3 ms                                                | 10.4 ms: 1.37x faster                                          |
| float                    | 116 ms                                                 | 85.0 ms: 1.37x faster                                          |
| deepcopy                 | 481 us                                                 | 353 us: 1.36x faster                                           |
| deepcopy_reduce          | 4.17 us                                                | 3.07 us: 1.36x faster                                          |
| hexiom                   | 10.3 ms                                                | 7.60 ms: 1.35x faster                                          |
| tornado_http             | 131 ms                                                 | 96.5 ms: 1.35x faster                                          |
| pycparser                | 1.57 sec                                               | 1.16 sec: 1.35x faster                                         |
| json_dumps               | 14.3 ms                                                | 10.6 ms: 1.35x faster                                          |
| pprint_pformat           | 2.10 sec                                               | 1.57 sec: 1.33x faster                                         |
| pprint_safe_repr         | 1.01 sec                                               | 766 ms: 1.32x faster                                           |
| regex_compile            | 186 ms                                                 | 141 ms: 1.31x faster                                           |
| mako                     | 16.3 ms                                                | 12.4 ms: 1.31x faster                                          |
| xml_etree_process        | 79.8 ms                                                | 61.0 ms: 1.31x faster                                          |
| sqlglot_normalize        | 141 ms                                                 | 109 ms: 1.30x faster                                           |
| 2to3                     | 346 ms                                                 | 273 ms: 1.26x faster                                           |
| mypy2                    | 442 ms                                                 | 351 ms: 1.26x faster                                           |
| sqlglot_optimize         | 68.7 ms                                                | 55.6 ms: 1.24x faster                                          |
| docutils                 | 3.26 sec                                               | 2.66 sec: 1.23x faster                                         |
| sympy_integrate          | 25.4 ms                                                | 20.8 ms: 1.22x faster                                          |
| sympy_sum                | 190 ms                                                 | 156 ms: 1.22x faster                                           |
| fannkuch                 | 527 ms                                                 | 434 ms: 1.22x faster                                           |
| sympy_str                | 337 ms                                                 | 282 ms: 1.20x faster                                           |
| sympy_expand             | 558 ms                                                 | 468 ms: 1.19x faster                                           |
| spectral_norm            | 163 ms                                                 | 137 ms: 1.19x faster                                           |
| scimark_fft              | 454 ms                                                 | 382 ms: 1.19x faster                                           |
| dask                     | 432 ms                                                 | 366 ms: 1.18x faster                                           |
| dulwich_log              | 77.0 ms                                                | 66.4 ms: 1.16x faster                                          |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 5.31 ms: 1.15x faster                                          |
| bench_thread_pool        | 966 us                                                 | 854 us: 1.13x faster                                           |
| nqueens                  | 107 ms                                                 | 94.4 ms: 1.13x faster                                          |
| xml_etree_generate       | 100.0 ms                                               | 89.1 ms: 1.12x faster                                          |
| json_loads               | 31.4 us                                                | 28.4 us: 1.11x faster                                          |
| create_gc_cycles         | 1.61 ms                                                | 1.46 ms: 1.10x faster                                          |
| mdp                      | 2.93 sec                                               | 2.68 sec: 1.09x faster                                         |
| json                     | 5.67 ms                                                | 5.19 ms: 1.09x faster                                          |
| pathlib                  | 20.3 ms                                                | 18.6 ms: 1.09x faster                                          |
| regex_v8                 | 26.2 ms                                                | 24.3 ms: 1.08x faster                                          |
| meteor_contest           | 119 ms                                                 | 111 ms: 1.07x faster                                           |
| sqlite_synth             | 3.02 us                                                | 2.81 us: 1.07x faster                                          |
| xml_etree_parse          | 171 ms                                                 | 160 ms: 1.07x faster                                           |
| xml_etree_iterparse      | 116 ms                                                 | 110 ms: 1.06x faster                                           |
| pickle_list              | 5.05 us                                                | 4.89 us: 1.03x faster                                          |
| pidigits                 | 190 ms                                                 | 188 ms: 1.02x faster                                           |
| asyncio_websockets       | 558 ms                                                 | 553 ms: 1.01x faster                                           |
| regex_dna                | 215 ms                                                 | 216 ms: 1.00x slower                                           |
| unpickle_list            | 5.10 us                                                | 5.28 us: 1.04x slower                                          |
| unpickle                 | 14.9 us                                                | 15.5 us: 1.05x slower                                          |
| async_generators         | 442 ms                                                 | 464 ms: 1.05x slower                                           |
| pickle                   | 10.7 us                                                | 11.2 us: 1.05x slower                                          |
| regex_effbot             | 3.41 ms                                                | 3.63 ms: 1.07x slower                                          |
| pickle_dict              | 30.0 us                                                | 34.0 us: 1.14x slower                                          |
| coverage                 | 82.0 ms                                                | 95.4 ms: 1.16x slower                                          |
| gc_traversal             | 3.43 ms                                                | 4.04 ms: 1.18x slower                                          |
| telco                    | 7.01 ms                                                | 8.31 ms: 1.19x slower                                          |
| python_startup_no_site   | 5.87 ms                                                | 9.10 ms: 1.55x slower                                          |
| Geometric mean           | (ref)                                                  | 1.29x faster                                                   |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231120-3.13.0a1+-7bb54b5-PYTHON_UOPS/bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.23x
- 95% likely to have a speedup of 1.23x
- 99% likely to have a speedup of 1.21x
