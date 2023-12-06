
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin
- machine: darwin-arm64
- commit hash: 7eaec09
- commit date: 2023-10-17
- overall geometric mean: 1.01x faster
- HPT reliability: 65.03%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| docutils       | 1.47 sec                                               | 1.52 sec: 1.03x slower                                         |
| Geometric mean | (ref)                                                  | 1.01x slower                                                   |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 281 ms                                                 | 283 ms: 1.01x slower                                           |
| float          | 53.0 ms                                                | 56.0 ms: 1.06x slower                                          |
| nbody          | 65.6 ms                                                | 75.6 ms: 1.15x slower                                          |
| Geometric mean | (ref)                                                  | 1.07x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_effbot   | 2.63 ms                                                | 2.56 ms: 1.03x faster                                          |
| regex_dna      | 152 ms                                                 | 149 ms: 1.02x faster                                           |
| regex_v8       | 16.1 ms                                                | 16.9 ms: 1.05x slower                                          |
| Geometric mean | (ref)                                                  | 1.00x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| json_dumps           | 7.63 ms                                                | 6.45 ms: 1.18x faster                                          |
| tomli_loads          | 1.47 sec                                               | 1.34 sec: 1.10x faster                                         |
| unpickle             | 9.67 us                                                | 9.16 us: 1.06x faster                                          |
| pickle_pure_python   | 201 us                                                 | 193 us: 1.04x faster                                           |
| unpickle_pure_python | 159 us                                                 | 158 us: 1.01x faster                                           |
| pickle_dict          | 18.0 us                                                | 17.9 us: 1.00x faster                                          |
| xml_etree_parse      | 108 ms                                                 | 111 ms: 1.02x slower                                           |
| pickle_list          | 2.81 us                                                | 2.89 us: 1.03x slower                                          |
| pickle               | 7.15 us                                                | 7.42 us: 1.04x slower                                          |
| xml_etree_iterparse  | 70.1 ms                                                | 75.4 ms: 1.08x slower                                          |
| json_loads           | 16.1 us                                                | 17.5 us: 1.09x slower                                          |
| xml_etree_process    | 35.1 ms                                                | 39.5 ms: 1.13x slower                                          |
| unpickle_list        | 2.65 us                                                | 3.13 us: 1.18x slower                                          |
| xml_etree_generate   | 48.3 ms                                                | 57.7 ms: 1.20x slower                                          |
| Geometric mean       | (ref)                                                  | 1.03x slower                                                   |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup_no_site | 10.2 ms                                                | 8.64 ms: 1.18x faster                                          |
| python_startup         | 12.4 ms                                                | 11.2 ms: 1.11x faster                                          |
| Geometric mean         | (ref)                                                  | 1.14x faster                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 8.53 ms                                                | 7.55 ms: 1.13x faster                                          |

All benchmarks:
===============

| Benchmark                | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 93.2 us: 3.60x faster                                          |
| asyncio_tcp              | 651 ms                                                 | 452 ms: 1.44x faster                                           |
| unpack_sequence          | 34.1 ns                                                | 26.4 ns: 1.29x faster                                          |
| coverage                 | 58.4 ms                                                | 47.0 ms: 1.24x faster                                          |
| sqlglot_parse            | 959 us                                                 | 796 us: 1.20x faster                                           |
| chaos                    | 49.4 ms                                                | 41.7 ms: 1.18x faster                                          |
| json_dumps               | 7.63 ms                                                | 6.45 ms: 1.18x faster                                          |
| python_startup_no_site   | 10.2 ms                                                | 8.64 ms: 1.18x faster                                          |
| generators               | 28.8 ms                                                | 24.7 ms: 1.16x faster                                          |
| raytrace                 | 207 ms                                                 | 179 ms: 1.16x faster                                           |
| deltablue                | 2.81 ms                                                | 2.43 ms: 1.16x faster                                          |
| sqlglot_transpile        | 1.12 ms                                                | 975 us: 1.15x faster                                           |
| mako                     | 8.53 ms                                                | 7.55 ms: 1.13x faster                                          |
| richards_super           | 39.2 ms                                                | 34.7 ms: 1.13x faster                                          |
| async_tree_none          | 286 ms                                                 | 254 ms: 1.13x faster                                           |
| python_startup           | 12.4 ms                                                | 11.2 ms: 1.11x faster                                          |
| asyncio_tcp_ssl          | 1.44 sec                                               | 1.31 sec: 1.10x faster                                         |
| tomli_loads              | 1.47 sec                                               | 1.34 sec: 1.10x faster                                         |
| crypto_pyaes             | 51.7 ms                                                | 48.7 ms: 1.06x faster                                          |
| unpickle                 | 9.67 us                                                | 9.16 us: 1.06x faster                                          |
| deepcopy_memo            | 26.3 us                                                | 25.1 us: 1.05x faster                                          |
| go                       | 109 ms                                                 | 105 ms: 1.04x faster                                           |
| pickle_pure_python       | 201 us                                                 | 193 us: 1.04x faster                                           |
| richards                 | 32.2 ms                                                | 31.2 ms: 1.03x faster                                          |
| regex_effbot             | 2.63 ms                                                | 2.56 ms: 1.03x faster                                          |
| scimark_sparse_mat_mult  | 3.19 ms                                                | 3.11 ms: 1.03x faster                                          |
| create_gc_cycles         | 716 us                                                 | 701 us: 1.02x faster                                           |
| regex_dna                | 152 ms                                                 | 149 ms: 1.02x faster                                           |
| async_tree_cpu_io_mixed  | 533 ms                                                 | 525 ms: 1.02x faster                                           |
| logging_simple           | 3.55 us                                                | 3.50 us: 1.01x faster                                          |
| scimark_lu               | 73.3 ms                                                | 72.5 ms: 1.01x faster                                          |
| coroutines               | 17.8 ms                                                | 17.6 ms: 1.01x faster                                          |
| spectral_norm            | 72.6 ms                                                | 72.0 ms: 1.01x faster                                          |
| unpickle_pure_python     | 159 us                                                 | 158 us: 1.01x faster                                           |
| gc_traversal             | 2.42 ms                                                | 2.40 ms: 1.01x faster                                          |
| async_tree_io            | 704 ms                                                 | 701 ms: 1.00x faster                                           |
| pickle_dict              | 18.0 us                                                | 17.9 us: 1.00x faster                                          |
| scimark_monte_carlo      | 46.5 ms                                                | 46.3 ms: 1.00x faster                                          |
| logging_format           | 3.78 us                                                | 3.79 us: 1.00x slower                                          |
| deepcopy                 | 223 us                                                 | 224 us: 1.01x slower                                           |
| pidigits                 | 281 ms                                                 | 283 ms: 1.01x slower                                           |
| dulwich_log              | 30.3 ms                                                | 30.5 ms: 1.01x slower                                          |
| comprehensions           | 16.1 us                                                | 16.3 us: 1.01x slower                                          |
| xml_etree_parse          | 108 ms                                                 | 111 ms: 1.02x slower                                           |
| pickle_list              | 2.81 us                                                | 2.89 us: 1.03x slower                                          |
| bench_mp_pool            | 43.9 ms                                                | 45.2 ms: 1.03x slower                                          |
| docutils                 | 1.47 sec                                               | 1.52 sec: 1.03x slower                                         |
| bench_thread_pool        | 474 us                                                 | 489 us: 1.03x slower                                           |
| pickle                   | 7.15 us                                                | 7.42 us: 1.04x slower                                          |
| deepcopy_reduce          | 1.91 us                                                | 1.99 us: 1.04x slower                                          |
| meteor_contest           | 73.5 ms                                                | 76.8 ms: 1.05x slower                                          |
| regex_v8                 | 16.1 ms                                                | 16.9 ms: 1.05x slower                                          |
| hexiom                   | 4.72 ms                                                | 4.94 ms: 1.05x slower                                          |
| nqueens                  | 59.8 ms                                                | 62.7 ms: 1.05x slower                                          |
| scimark_fft              | 200 ms                                                 | 210 ms: 1.05x slower                                           |
| pyflate                  | 310 ms                                                 | 328 ms: 1.06x slower                                           |
| float                    | 53.0 ms                                                | 56.0 ms: 1.06x slower                                          |
| mdp                      | 1.55 sec                                               | 1.65 sec: 1.07x slower                                         |
| json                     | 2.78 ms                                                | 2.97 ms: 1.07x slower                                          |
| fannkuch                 | 261 ms                                                 | 281 ms: 1.07x slower                                           |
| xml_etree_iterparse      | 70.1 ms                                                | 75.4 ms: 1.08x slower                                          |
| sqlglot_normalize        | 171 ms                                                 | 184 ms: 1.08x slower                                           |
| json_loads               | 16.1 us                                                | 17.5 us: 1.09x slower                                          |
| pathlib                  | 27.2 ms                                                | 29.9 ms: 1.10x slower                                          |
| sqlglot_optimize         | 31.1 ms                                                | 34.3 ms: 1.10x slower                                          |
| xml_etree_process        | 35.1 ms                                                | 39.5 ms: 1.13x slower                                          |
| nbody                    | 65.6 ms                                                | 75.6 ms: 1.15x slower                                          |
| unpickle_list            | 2.65 us                                                | 3.13 us: 1.18x slower                                          |
| xml_etree_generate       | 48.3 ms                                                | 57.7 ms: 1.20x slower                                          |
| scimark_sor              | 82.6 ms                                                | 104 ms: 1.26x slower                                           |
| sqlite_synth             | 1.27 us                                                | 1.63 us: 1.29x slower                                          |
| mypy2                    | 195 ms                                                 | 262 ms: 1.34x slower                                           |
| telco                    | 3.41 ms                                                | 4.76 ms: 1.40x slower                                          |
| async_generators         | 196 ms                                                 | 309 ms: 1.57x slower                                           |
| Geometric mean           | (ref)                                                  | 1.01x faster                                                   |

Benchmark hidden because not significant (4): tornado_http, async_tree_memoization, pycparser, logging_silent
Ignored benchmarks (20) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pprint_pformat, pprint_safe_repr, pylint, regex_compile, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 65.03% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
