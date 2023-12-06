
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin
- machine: darwin-arm64
- commit hash: a98d4fe
- commit date: 2023-09-13
- overall geometric mean: 1.00x slower
- HPT reliability: 97.00%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-darwin-arm64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| docutils       | 1.47 sec                                               | 1.53 sec: 1.04x slower                                        |
| Geometric mean | (ref)                                                  | 1.02x slower                                                  |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-darwin-arm64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| pidigits       | 281 ms                                                 | 282 ms: 1.01x slower                                          |
| float          | 53.0 ms                                                | 56.8 ms: 1.07x slower                                         |
| nbody          | 65.6 ms                                                | 82.4 ms: 1.26x slower                                         |
| Geometric mean | (ref)                                                  | 1.11x slower                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-darwin-arm64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_dna      | 152 ms                                                 | 140 ms: 1.09x faster                                          |
| regex_effbot   | 2.63 ms                                                | 2.50 ms: 1.05x faster                                         |
| regex_v8       | 16.1 ms                                                | 16.4 ms: 1.02x slower                                         |
| regex_compile  | 76.7 ms                                                | 82.1 ms: 1.07x slower                                         |
| Geometric mean | (ref)                                                  | 1.01x faster                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-darwin-arm64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| json_dumps           | 7.63 ms                                                | 6.47 ms: 1.18x faster                                         |
| unpickle             | 9.67 us                                                | 9.21 us: 1.05x faster                                         |
| tomli_loads          | 1.47 sec                                               | 1.41 sec: 1.04x faster                                        |
| pickle_pure_python   | 201 us                                                 | 196 us: 1.02x faster                                          |
| pickle_dict          | 18.0 us                                                | 17.9 us: 1.00x faster                                         |
| pickle_list          | 2.81 us                                                | 2.87 us: 1.02x slower                                         |
| xml_etree_parse      | 108 ms                                                 | 111 ms: 1.02x slower                                          |
| unpickle_pure_python | 159 us                                                 | 165 us: 1.03x slower                                          |
| pickle               | 7.15 us                                                | 7.45 us: 1.04x slower                                         |
| json_loads           | 16.1 us                                                | 17.5 us: 1.09x slower                                         |
| xml_etree_iterparse  | 70.1 ms                                                | 76.8 ms: 1.09x slower                                         |
| xml_etree_process    | 35.1 ms                                                | 39.4 ms: 1.12x slower                                         |
| xml_etree_generate   | 48.3 ms                                                | 57.7 ms: 1.20x slower                                         |
| unpickle_list        | 2.65 us                                                | 3.24 us: 1.22x slower                                         |
| Geometric mean       | (ref)                                                  | 1.04x slower                                                  |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-darwin-arm64-brandtbucher-justin-3.13.0a0-a98d4fe |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup_no_site | 10.2 ms                                                | 9.45 ms: 1.08x faster                                         |
| python_startup         | 12.4 ms                                                | 12.1 ms: 1.03x faster                                         |
| Geometric mean         | (ref)                                                  | 1.05x faster                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-darwin-arm64-brandtbucher-justin-3.13.0a0-a98d4fe |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 8.53 ms                                                | 7.67 ms: 1.11x faster                                         |

All benchmarks:
===============

| Benchmark                | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-darwin-arm64-brandtbucher-justin-3.13.0a0-a98d4fe |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 94.0 us: 3.57x faster                                         |
| asyncio_tcp              | 651 ms                                                 | 441 ms: 1.48x faster                                          |
| unpack_sequence          | 34.1 ns                                                | 27.0 ns: 1.26x faster                                         |
| coverage                 | 58.4 ms                                                | 47.0 ms: 1.24x faster                                         |
| sqlglot_parse            | 959 us                                                 | 808 us: 1.19x faster                                          |
| json_dumps               | 7.63 ms                                                | 6.47 ms: 1.18x faster                                         |
| chaos                    | 49.4 ms                                                | 42.5 ms: 1.16x faster                                         |
| generators               | 28.8 ms                                                | 24.9 ms: 1.15x faster                                         |
| raytrace                 | 207 ms                                                 | 179 ms: 1.15x faster                                          |
| sqlglot_transpile        | 1.12 ms                                                | 987 us: 1.14x faster                                          |
| async_tree_none          | 286 ms                                                 | 252 ms: 1.13x faster                                          |
| asyncio_tcp_ssl          | 1.44 sec                                               | 1.28 sec: 1.13x faster                                        |
| deltablue                | 2.81 ms                                                | 2.51 ms: 1.12x faster                                         |
| mako                     | 8.53 ms                                                | 7.67 ms: 1.11x faster                                         |
| regex_dna                | 152 ms                                                 | 140 ms: 1.09x faster                                          |
| python_startup_no_site   | 10.2 ms                                                | 9.45 ms: 1.08x faster                                         |
| crypto_pyaes             | 51.7 ms                                                | 49.1 ms: 1.05x faster                                         |
| unpickle                 | 9.67 us                                                | 9.21 us: 1.05x faster                                         |
| regex_effbot             | 2.63 ms                                                | 2.50 ms: 1.05x faster                                         |
| tomli_loads              | 1.47 sec                                               | 1.41 sec: 1.04x faster                                        |
| richards_super           | 39.2 ms                                                | 37.7 ms: 1.04x faster                                         |
| python_startup           | 12.4 ms                                                | 12.1 ms: 1.03x faster                                         |
| async_tree_memoization   | 336 ms                                                 | 328 ms: 1.02x faster                                          |
| pickle_pure_python       | 201 us                                                 | 196 us: 1.02x faster                                          |
| async_tree_cpu_io_mixed  | 533 ms                                                 | 523 ms: 1.02x faster                                          |
| deepcopy_memo            | 26.3 us                                                | 25.9 us: 1.02x faster                                         |
| create_gc_cycles         | 716 us                                                 | 707 us: 1.01x faster                                          |
| async_tree_io            | 704 ms                                                 | 697 ms: 1.01x faster                                          |
| scimark_monte_carlo      | 46.5 ms                                                | 46.0 ms: 1.01x faster                                         |
| scimark_lu               | 73.3 ms                                                | 72.7 ms: 1.01x faster                                         |
| pickle_dict              | 18.0 us                                                | 17.9 us: 1.00x faster                                         |
| gc_traversal             | 2.42 ms                                                | 2.41 ms: 1.00x faster                                         |
| mypy2                    | 195 ms                                                 | 196 ms: 1.00x slower                                          |
| pidigits                 | 281 ms                                                 | 282 ms: 1.01x slower                                          |
| spectral_norm            | 72.6 ms                                                | 73.1 ms: 1.01x slower                                         |
| coroutines               | 17.8 ms                                                | 17.9 ms: 1.01x slower                                         |
| logging_simple           | 3.55 us                                                | 3.59 us: 1.01x slower                                         |
| dulwich_log              | 30.3 ms                                                | 30.8 ms: 1.02x slower                                         |
| deepcopy                 | 223 us                                                 | 226 us: 1.02x slower                                          |
| regex_v8                 | 16.1 ms                                                | 16.4 ms: 1.02x slower                                         |
| pickle_list              | 2.81 us                                                | 2.87 us: 1.02x slower                                         |
| xml_etree_parse          | 108 ms                                                 | 111 ms: 1.02x slower                                          |
| logging_format           | 3.78 us                                                | 3.87 us: 1.03x slower                                         |
| unpickle_pure_python     | 159 us                                                 | 165 us: 1.03x slower                                          |
| bench_thread_pool        | 474 us                                                 | 492 us: 1.04x slower                                          |
| docutils                 | 1.47 sec                                               | 1.53 sec: 1.04x slower                                        |
| pickle                   | 7.15 us                                                | 7.45 us: 1.04x slower                                         |
| logging_silent           | 68.1 ns                                                | 71.1 ns: 1.04x slower                                         |
| comprehensions           | 16.1 us                                                | 16.8 us: 1.04x slower                                         |
| meteor_contest           | 73.5 ms                                                | 77.2 ms: 1.05x slower                                         |
| scimark_sparse_mat_mult  | 3.19 ms                                                | 3.35 ms: 1.05x slower                                         |
| richards                 | 32.2 ms                                                | 34.0 ms: 1.05x slower                                         |
| deepcopy_reduce          | 1.91 us                                                | 2.02 us: 1.06x slower                                         |
| regex_compile            | 76.7 ms                                                | 82.1 ms: 1.07x slower                                         |
| float                    | 53.0 ms                                                | 56.8 ms: 1.07x slower                                         |
| nqueens                  | 59.8 ms                                                | 64.4 ms: 1.08x slower                                         |
| pprint_pformat           | 954 ms                                                 | 1.03 sec: 1.08x slower                                        |
| json                     | 2.78 ms                                                | 3.00 ms: 1.08x slower                                         |
| pprint_safe_repr         | 466 ms                                                 | 504 ms: 1.08x slower                                          |
| mdp                      | 1.55 sec                                               | 1.67 sec: 1.08x slower                                        |
| bench_mp_pool            | 43.9 ms                                                | 47.6 ms: 1.08x slower                                         |
| sqlglot_normalize        | 171 ms                                                 | 185 ms: 1.09x slower                                          |
| json_loads               | 16.1 us                                                | 17.5 us: 1.09x slower                                         |
| pyflate                  | 310 ms                                                 | 338 ms: 1.09x slower                                          |
| hexiom                   | 4.72 ms                                                | 5.15 ms: 1.09x slower                                         |
| xml_etree_iterparse      | 70.1 ms                                                | 76.8 ms: 1.09x slower                                         |
| scimark_fft              | 200 ms                                                 | 221 ms: 1.11x slower                                          |
| sqlglot_optimize         | 31.1 ms                                                | 34.6 ms: 1.11x slower                                         |
| fannkuch                 | 261 ms                                                 | 291 ms: 1.12x slower                                          |
| xml_etree_process        | 35.1 ms                                                | 39.4 ms: 1.12x slower                                         |
| pathlib                  | 27.2 ms                                                | 32.5 ms: 1.19x slower                                         |
| xml_etree_generate       | 48.3 ms                                                | 57.7 ms: 1.20x slower                                         |
| unpickle_list            | 2.65 us                                                | 3.24 us: 1.22x slower                                         |
| sqlite_synth             | 1.27 us                                                | 1.60 us: 1.26x slower                                         |
| nbody                    | 65.6 ms                                                | 82.4 ms: 1.26x slower                                         |
| scimark_sor              | 82.6 ms                                                | 106 ms: 1.29x slower                                          |
| telco                    | 3.41 ms                                                | 4.71 ms: 1.38x slower                                         |
| async_generators         | 196 ms                                                 | 311 ms: 1.58x slower                                          |
| Geometric mean           | (ref)                                                  | 1.00x slower                                                  |

Benchmark hidden because not significant (3): pycparser, go, tornado_http
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
Ignored benchmarks (1) of results/bm-20230913-3.13.0a0-a98d4fe/bm-20230913-darwin-arm64-brandtbucher-justin-3.13.0a0-a98d4fe.json: dask


# HPT report

- Reliability score: 97.00% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
