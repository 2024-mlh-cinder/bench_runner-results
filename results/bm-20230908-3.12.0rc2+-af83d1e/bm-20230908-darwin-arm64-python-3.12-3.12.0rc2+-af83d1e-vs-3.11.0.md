
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: darwin-arm64
- commit hash: af83d1e
- commit date: 2023-09-08
- overall geometric mean: 1.01x faster
- HPT reliability: 62.76%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230908-darwin-arm64-python-3.12-3.12.0rc2+-af83d1e |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| 2to3           | 161 ms                                                 | 170 ms: 1.05x slower                                    |
| docutils       | 1.47 sec                                               | 1.53 sec: 1.04x slower                                  |
| Geometric mean | (ref)                                                  | 1.03x slower                                            |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230908-darwin-arm64-python-3.12-3.12.0rc2+-af83d1e |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| pidigits       | 281 ms                                                 | 282 ms: 1.00x slower                                    |
| nbody          | 65.6 ms                                                | 68.4 ms: 1.04x slower                                   |
| float          | 53.0 ms                                                | 57.9 ms: 1.09x slower                                   |
| Geometric mean | (ref)                                                  | 1.05x slower                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230908-darwin-arm64-python-3.12-3.12.0rc2+-af83d1e |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_v8       | 16.1 ms                                                | 15.6 ms: 1.03x faster                                   |
| regex_effbot   | 2.63 ms                                                | 2.55 ms: 1.03x faster                                   |
| regex_dna      | 152 ms                                                 | 150 ms: 1.02x faster                                    |
| regex_compile  | 76.7 ms                                                | 75.7 ms: 1.01x faster                                   |
| Geometric mean | (ref)                                                  | 1.02x faster                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230908-darwin-arm64-python-3.12-3.12.0rc2+-af83d1e |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| json_dumps           | 7.63 ms                                                | 6.44 ms: 1.18x faster                                   |
| unpickle_pure_python | 159 us                                                 | 144 us: 1.11x faster                                    |
| pickle_pure_python   | 201 us                                                 | 190 us: 1.06x faster                                    |
| tomli_loads          | 1.47 sec                                               | 1.39 sec: 1.06x faster                                  |
| unpickle             | 9.67 us                                                | 9.30 us: 1.04x faster                                   |
| pickle_dict          | 18.0 us                                                | 18.0 us: 1.00x slower                                   |
| xml_etree_parse      | 108 ms                                                 | 109 ms: 1.01x slower                                    |
| pickle_list          | 2.81 us                                                | 2.87 us: 1.02x slower                                   |
| pickle               | 7.15 us                                                | 7.43 us: 1.04x slower                                   |
| xml_etree_iterparse  | 70.1 ms                                                | 74.1 ms: 1.06x slower                                   |
| json_loads           | 16.1 us                                                | 17.6 us: 1.09x slower                                   |
| xml_etree_process    | 35.1 ms                                                | 38.6 ms: 1.10x slower                                   |
| xml_etree_generate   | 48.3 ms                                                | 55.7 ms: 1.16x slower                                   |
| unpickle_list        | 2.65 us                                                | 3.29 us: 1.24x slower                                   |
| Geometric mean       | (ref)                                                  | 1.02x slower                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230908-darwin-arm64-python-3.12-3.12.0rc2+-af83d1e |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| python_startup_no_site | 10.2 ms                                                | 9.69 ms: 1.05x faster                                   |
| python_startup         | 12.4 ms                                                | 11.8 ms: 1.05x faster                                   |
| Geometric mean         | (ref)                                                  | 1.05x faster                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230908-darwin-arm64-python-3.12-3.12.0rc2+-af83d1e |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------:|
| mako      | 8.53 ms                                                | 7.53 ms: 1.13x faster                                   |

All benchmarks:
===============

| Benchmark                | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230908-darwin-arm64-python-3.12-3.12.0rc2+-af83d1e |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 89.1 us: 3.77x faster                                   |
| asyncio_tcp              | 651 ms                                                 | 446 ms: 1.46x faster                                    |
| json_dumps               | 7.63 ms                                                | 6.44 ms: 1.18x faster                                   |
| unpack_sequence          | 34.1 ns                                                | 28.9 ns: 1.18x faster                                   |
| asyncio_tcp_ssl          | 1.44 sec                                               | 1.24 sec: 1.16x faster                                  |
| coverage                 | 58.4 ms                                                | 50.9 ms: 1.15x faster                                   |
| mako                     | 8.53 ms                                                | 7.53 ms: 1.13x faster                                   |
| richards_super           | 39.2 ms                                                | 35.0 ms: 1.12x faster                                   |
| hexiom                   | 4.72 ms                                                | 4.25 ms: 1.11x faster                                   |
| unpickle_pure_python     | 159 us                                                 | 144 us: 1.11x faster                                    |
| async_tree_none          | 286 ms                                                 | 259 ms: 1.10x faster                                    |
| async_tree_memoization   | 336 ms                                                 | 306 ms: 1.10x faster                                    |
| chaos                    | 49.4 ms                                                | 45.2 ms: 1.09x faster                                   |
| deltablue                | 2.81 ms                                                | 2.59 ms: 1.09x faster                                   |
| deepcopy_memo            | 26.3 us                                                | 24.6 us: 1.07x faster                                   |
| sqlglot_parse            | 959 us                                                 | 898 us: 1.07x faster                                    |
| pickle_pure_python       | 201 us                                                 | 190 us: 1.06x faster                                    |
| tomli_loads              | 1.47 sec                                               | 1.39 sec: 1.06x faster                                  |
| async_tree_io            | 704 ms                                                 | 669 ms: 1.05x faster                                    |
| python_startup_no_site   | 10.2 ms                                                | 9.69 ms: 1.05x faster                                   |
| python_startup           | 12.4 ms                                                | 11.8 ms: 1.05x faster                                   |
| pycparser                | 698 ms                                                 | 665 ms: 1.05x faster                                    |
| sqlglot_transpile        | 1.12 ms                                                | 1.08 ms: 1.04x faster                                   |
| unpickle                 | 9.67 us                                                | 9.30 us: 1.04x faster                                   |
| regex_v8                 | 16.1 ms                                                | 15.6 ms: 1.03x faster                                   |
| regex_effbot             | 2.63 ms                                                | 2.55 ms: 1.03x faster                                   |
| scimark_lu               | 73.3 ms                                                | 71.3 ms: 1.03x faster                                   |
| richards                 | 32.2 ms                                                | 31.4 ms: 1.03x faster                                   |
| sqlalchemy_imperative    | 7.20 ms                                                | 7.02 ms: 1.03x faster                                   |
| async_tree_cpu_io_mixed  | 533 ms                                                 | 521 ms: 1.02x faster                                    |
| create_gc_cycles         | 716 us                                                 | 700 us: 1.02x faster                                    |
| comprehensions           | 16.1 us                                                | 15.8 us: 1.02x faster                                   |
| go                       | 109 ms                                                 | 107 ms: 1.02x faster                                    |
| regex_dna                | 152 ms                                                 | 150 ms: 1.02x faster                                    |
| generators               | 28.8 ms                                                | 28.3 ms: 1.02x faster                                   |
| regex_compile            | 76.7 ms                                                | 75.7 ms: 1.01x faster                                   |
| meteor_contest           | 73.5 ms                                                | 72.8 ms: 1.01x faster                                   |
| scimark_sparse_mat_mult  | 3.19 ms                                                | 3.17 ms: 1.01x faster                                   |
| gc_traversal             | 2.42 ms                                                | 2.40 ms: 1.01x faster                                   |
| scimark_fft              | 200 ms                                                 | 198 ms: 1.01x faster                                    |
| logging_silent           | 68.1 ns                                                | 67.8 ns: 1.00x faster                                   |
| pickle_dict              | 18.0 us                                                | 18.0 us: 1.00x slower                                   |
| pidigits                 | 281 ms                                                 | 282 ms: 1.00x slower                                    |
| crypto_pyaes             | 51.7 ms                                                | 52.0 ms: 1.00x slower                                   |
| deepcopy                 | 223 us                                                 | 225 us: 1.01x slower                                    |
| nqueens                  | 59.8 ms                                                | 60.4 ms: 1.01x slower                                   |
| xml_etree_parse          | 108 ms                                                 | 109 ms: 1.01x slower                                    |
| fannkuch                 | 261 ms                                                 | 266 ms: 1.02x slower                                    |
| pickle_list              | 2.81 us                                                | 2.87 us: 1.02x slower                                   |
| coroutines               | 17.8 ms                                                | 18.2 ms: 1.02x slower                                   |
| bench_thread_pool        | 474 us                                                 | 486 us: 1.02x slower                                    |
| spectral_norm            | 72.6 ms                                                | 74.9 ms: 1.03x slower                                   |
| logging_simple           | 3.55 us                                                | 3.67 us: 1.03x slower                                   |
| sqlalchemy_declarative   | 62.6 ms                                                | 65.0 ms: 1.04x slower                                   |
| docutils                 | 1.47 sec                                               | 1.53 sec: 1.04x slower                                  |
| pickle                   | 7.15 us                                                | 7.43 us: 1.04x slower                                   |
| nbody                    | 65.6 ms                                                | 68.4 ms: 1.04x slower                                   |
| pprint_pformat           | 954 ms                                                 | 998 ms: 1.05x slower                                    |
| logging_format           | 3.78 us                                                | 3.97 us: 1.05x slower                                   |
| pprint_safe_repr         | 466 ms                                                 | 491 ms: 1.05x slower                                    |
| bench_mp_pool            | 43.9 ms                                                | 46.3 ms: 1.05x slower                                   |
| pyflate                  | 310 ms                                                 | 327 ms: 1.05x slower                                    |
| 2to3                     | 161 ms                                                 | 170 ms: 1.05x slower                                    |
| xml_etree_iterparse      | 70.1 ms                                                | 74.1 ms: 1.06x slower                                   |
| deepcopy_reduce          | 1.91 us                                                | 2.03 us: 1.06x slower                                   |
| scimark_monte_carlo      | 46.5 ms                                                | 49.8 ms: 1.07x slower                                   |
| mdp                      | 1.55 sec                                               | 1.67 sec: 1.08x slower                                  |
| sqlglot_normalize        | 171 ms                                                 | 186 ms: 1.09x slower                                    |
| telco                    | 3.41 ms                                                | 3.71 ms: 1.09x slower                                   |
| json_loads               | 16.1 us                                                | 17.6 us: 1.09x slower                                   |
| float                    | 53.0 ms                                                | 57.9 ms: 1.09x slower                                   |
| json                     | 2.78 ms                                                | 3.04 ms: 1.10x slower                                   |
| xml_etree_process        | 35.1 ms                                                | 38.6 ms: 1.10x slower                                   |
| sqlglot_optimize         | 31.1 ms                                                | 34.2 ms: 1.10x slower                                   |
| scimark_sor              | 82.6 ms                                                | 94.2 ms: 1.14x slower                                   |
| xml_etree_generate       | 48.3 ms                                                | 55.7 ms: 1.16x slower                                   |
| raytrace                 | 207 ms                                                 | 245 ms: 1.18x slower                                    |
| pathlib                  | 27.2 ms                                                | 32.3 ms: 1.19x slower                                   |
| unpickle_list            | 2.65 us                                                | 3.29 us: 1.24x slower                                   |
| sqlite_synth             | 1.27 us                                                | 1.59 us: 1.25x slower                                   |
| mypy2                    | 195 ms                                                 | 256 ms: 1.32x slower                                    |
| async_generators         | 196 ms                                                 | 305 ms: 1.55x slower                                    |
| Geometric mean           | (ref)                                                  | 1.01x faster                                            |

Benchmark hidden because not significant (2): tornado_http, dulwich_log
Ignored benchmarks (14) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
Ignored benchmarks (1) of results/bm-20230908-3.12.0rc2+-af83d1e/bm-20230908-darwin-arm64-python-3.12-3.12.0rc2+-af83d1e.json: dask


# HPT report

- Reliability score: 62.76% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
