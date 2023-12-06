
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 7eaec09
- commit date: 2023-10-17
- overall geometric mean: 1.00x slower
- HPT reliability: 99.47%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.70 sec: 1.03x slower                                         |
| tornado_http   | 96.3 ms                                                | 98.0 ms: 1.02x slower                                          |
| Geometric mean | (ref)                                                  | 1.02x slower                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 195 ms: 1.02x faster                                           |
| nbody          | 93.1 ms                                                | 91.9 ms: 1.01x faster                                          |
| float          | 77.2 ms                                                | 82.4 ms: 1.07x slower                                          |
| Geometric mean | (ref)                                                  | 1.01x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.51 ms: 1.14x faster                                          |
| regex_compile  | 138 ms                                                 | 143 ms: 1.04x slower                                           |
| regex_dna      | 204 ms                                                 | 215 ms: 1.06x slower                                           |
| regex_v8       | 22.0 ms                                                | 25.2 ms: 1.14x slower                                          |
| Geometric mean | (ref)                                                  | 1.02x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 10.5 ms: 1.19x faster                                          |
| tomli_loads          | 2.22 sec                                               | 2.06 sec: 1.08x faster                                         |
| pickle_pure_python   | 306 us                                                 | 310 us: 1.01x slower                                           |
| xml_etree_parse      | 158 ms                                                 | 161 ms: 1.02x slower                                           |
| unpickle_pure_python | 228 us                                                 | 235 us: 1.03x slower                                           |
| xml_etree_iterparse  | 104 ms                                                 | 109 ms: 1.05x slower                                           |
| unpickle_list        | 4.91 us                                                | 5.17 us: 1.05x slower                                          |
| json_loads           | 26.5 us                                                | 28.0 us: 1.06x slower                                          |
| pickle_dict          | 31.1 us                                                | 34.0 us: 1.09x slower                                          |
| unpickle             | 13.7 us                                                | 15.2 us: 1.11x slower                                          |
| pickle               | 10.1 us                                                | 11.3 us: 1.12x slower                                          |
| xml_etree_process    | 53.9 ms                                                | 61.0 ms: 1.13x slower                                          |
| xml_etree_generate   | 76.2 ms                                                | 88.3 ms: 1.16x slower                                          |
| pickle_list          | 4.11 us                                                | 5.00 us: 1.22x slower                                          |
| Geometric mean       | (ref)                                                  | 1.05x slower                                                   |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.94 ms: 1.15x slower                                          |
| python_startup         | 8.52 ms                                                | 10.2 ms: 1.19x slower                                          |
| Geometric mean         | (ref)                                                  | 1.17x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 11.5 ms: 1.14x slower                                          |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 161 us: 3.01x faster                                           |
| generators               | 73.5 ms                                                | 31.4 ms: 2.34x faster                                          |
| asyncio_tcp              | 922 ms                                                 | 492 ms: 1.87x faster                                           |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.79 sec: 1.75x faster                                         |
| json_dumps               | 12.6 ms                                                | 10.5 ms: 1.19x faster                                          |
| async_tree_none          | 526 ms                                                 | 444 ms: 1.18x faster                                           |
| mypy2                    | 420 ms                                                 | 356 ms: 1.18x faster                                           |
| regex_effbot             | 3.99 ms                                                | 3.51 ms: 1.14x faster                                          |
| coverage                 | 100 ms                                                 | 89.9 ms: 1.11x faster                                          |
| coroutines               | 25.5 ms                                                | 23.0 ms: 1.11x faster                                          |
| async_tree_memoization   | 627 ms                                                 | 571 ms: 1.10x faster                                           |
| async_tree_io            | 1.30 sec                                               | 1.19 sec: 1.09x faster                                         |
| tomli_loads              | 2.22 sec                                               | 2.06 sec: 1.08x faster                                         |
| sqlglot_parse            | 1.40 ms                                                | 1.31 ms: 1.07x faster                                          |
| chaos                    | 69.2 ms                                                | 65.0 ms: 1.06x faster                                          |
| richards_super           | 56.8 ms                                                | 53.9 ms: 1.05x faster                                          |
| sqlglot_transpile        | 1.70 ms                                                | 1.64 ms: 1.04x faster                                          |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 720 ms: 1.03x faster                                           |
| gc_traversal             | 4.02 ms                                                | 3.95 ms: 1.02x faster                                          |
| pidigits                 | 198 ms                                                 | 195 ms: 1.02x faster                                           |
| create_gc_cycles         | 1.49 ms                                                | 1.46 ms: 1.02x faster                                          |
| nbody                    | 93.1 ms                                                | 91.9 ms: 1.01x faster                                          |
| raytrace                 | 297 ms                                                 | 293 ms: 1.01x faster                                           |
| crypto_pyaes             | 74.7 ms                                                | 74.2 ms: 1.01x faster                                          |
| sqlglot_normalize        | 108 ms                                                 | 109 ms: 1.01x slower                                           |
| logging_simple           | 6.03 us                                                | 6.10 us: 1.01x slower                                          |
| pickle_pure_python       | 306 us                                                 | 310 us: 1.01x slower                                           |
| xml_etree_parse          | 158 ms                                                 | 161 ms: 1.02x slower                                           |
| tornado_http             | 96.3 ms                                                | 98.0 ms: 1.02x slower                                          |
| comprehensions           | 22.4 us                                                | 22.9 us: 1.02x slower                                          |
| logging_format           | 6.68 us                                                | 6.85 us: 1.02x slower                                          |
| docutils                 | 2.63 sec                                               | 2.70 sec: 1.03x slower                                         |
| unpickle_pure_python     | 228 us                                                 | 235 us: 1.03x slower                                           |
| sqlglot_optimize         | 53.1 ms                                                | 54.7 ms: 1.03x slower                                          |
| bench_thread_pool        | 819 us                                                 | 844 us: 1.03x slower                                           |
| regex_compile            | 138 ms                                                 | 143 ms: 1.04x slower                                           |
| richards                 | 45.7 ms                                                | 47.6 ms: 1.04x slower                                          |
| meteor_contest           | 107 ms                                                 | 111 ms: 1.04x slower                                           |
| json                     | 4.94 ms                                                | 5.18 ms: 1.05x slower                                          |
| xml_etree_iterparse      | 104 ms                                                 | 109 ms: 1.05x slower                                           |
| nqueens                  | 83.4 ms                                                | 87.6 ms: 1.05x slower                                          |
| deltablue                | 3.67 ms                                                | 3.86 ms: 1.05x slower                                          |
| unpickle_list            | 4.91 us                                                | 5.17 us: 1.05x slower                                          |
| pathlib                  | 18.2 ms                                                | 19.2 ms: 1.05x slower                                          |
| regex_dna                | 204 ms                                                 | 215 ms: 1.06x slower                                           |
| deepcopy                 | 342 us                                                 | 362 us: 1.06x slower                                           |
| json_loads               | 26.5 us                                                | 28.0 us: 1.06x slower                                          |
| fannkuch                 | 388 ms                                                 | 412 ms: 1.06x slower                                           |
| float                    | 77.2 ms                                                | 82.4 ms: 1.07x slower                                          |
| dulwich_log              | 63.7 ms                                                | 68.3 ms: 1.07x slower                                          |
| deepcopy_reduce          | 2.94 us                                                | 3.16 us: 1.07x slower                                          |
| go                       | 140 ms                                                 | 151 ms: 1.08x slower                                           |
| scimark_monte_carlo      | 68.1 ms                                                | 73.4 ms: 1.08x slower                                          |
| pickle_dict              | 31.1 us                                                | 34.0 us: 1.09x slower                                          |
| scimark_lu               | 110 ms                                                 | 122 ms: 1.11x slower                                           |
| logging_silent           | 101 ns                                                 | 112 ns: 1.11x slower                                           |
| pprint_pformat           | 1.46 sec                                               | 1.62 sec: 1.11x slower                                         |
| scimark_sor              | 118 ms                                                 | 131 ms: 1.11x slower                                           |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 5.00 ms: 1.11x slower                                          |
| hexiom                   | 6.37 ms                                                | 7.09 ms: 1.11x slower                                          |
| scimark_fft              | 328 ms                                                 | 365 ms: 1.11x slower                                           |
| unpickle                 | 13.7 us                                                | 15.2 us: 1.11x slower                                          |
| sqlite_synth             | 2.52 us                                                | 2.82 us: 1.12x slower                                          |
| pickle                   | 10.1 us                                                | 11.3 us: 1.12x slower                                          |
| xml_etree_process        | 53.9 ms                                                | 61.0 ms: 1.13x slower                                          |
| pprint_safe_repr         | 701 ms                                                 | 801 ms: 1.14x slower                                           |
| regex_v8                 | 22.0 ms                                                | 25.2 ms: 1.14x slower                                          |
| mako                     | 10.1 ms                                                | 11.5 ms: 1.14x slower                                          |
| deepcopy_memo            | 37.0 us                                                | 42.5 us: 1.15x slower                                          |
| python_startup_no_site   | 6.01 ms                                                | 6.94 ms: 1.15x slower                                          |
| xml_etree_generate       | 76.2 ms                                                | 88.3 ms: 1.16x slower                                          |
| spectral_norm            | 100 ms                                                 | 117 ms: 1.17x slower                                           |
| pyflate                  | 418 ms                                                 | 497 ms: 1.19x slower                                           |
| python_startup           | 8.52 ms                                                | 10.2 ms: 1.19x slower                                          |
| pickle_list              | 4.11 us                                                | 5.00 us: 1.22x slower                                          |
| telco                    | 6.58 ms                                                | 8.56 ms: 1.30x slower                                          |
| async_generators         | 368 ms                                                 | 482 ms: 1.31x slower                                           |
| unpack_sequence          | 43.1 ns                                                | 58.0 ns: 1.35x slower                                          |
| Geometric mean           | (ref)                                                  | 1.00x slower                                                   |

Benchmark hidden because not significant (3): pycparser, mdp, bench_mp_pool
Ignored benchmarks (19) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.47% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x