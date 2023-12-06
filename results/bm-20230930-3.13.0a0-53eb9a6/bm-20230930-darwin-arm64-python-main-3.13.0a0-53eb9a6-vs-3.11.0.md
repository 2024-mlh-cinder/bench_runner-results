
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: darwin-arm64
- commit hash: 53eb9a6
- commit date: 2023-09-30
- overall geometric mean: 1.03x faster
- HPT reliability: 70.02%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230930-darwin-arm64-python-main-3.13.0a0-53eb9a6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| docutils       | 1.47 sec                                               | 1.49 sec: 1.01x slower                                |
| Geometric mean | (ref)                                                  | 1.00x faster                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230930-darwin-arm64-python-main-3.13.0a0-53eb9a6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pidigits       | 281 ms                                                 | 281 ms: 1.00x slower                                  |
| float          | 53.0 ms                                                | 53.4 ms: 1.01x slower                                 |
| nbody          | 65.6 ms                                                | 66.1 ms: 1.01x slower                                 |
| Geometric mean | (ref)                                                  | 1.01x slower                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230930-darwin-arm64-python-main-3.13.0a0-53eb9a6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_dna      | 152 ms                                                 | 140 ms: 1.09x faster                                  |
| regex_effbot   | 2.63 ms                                                | 2.51 ms: 1.05x faster                                 |
| regex_compile  | 76.7 ms                                                | 75.8 ms: 1.01x faster                                 |
| regex_v8       | 16.1 ms                                                | 16.1 ms: 1.00x slower                                 |
| Geometric mean | (ref)                                                  | 1.04x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230930-darwin-arm64-python-main-3.13.0a0-53eb9a6 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| json_dumps           | 7.63 ms                                                | 6.67 ms: 1.14x faster                                 |
| unpickle             | 9.67 us                                                | 9.11 us: 1.06x faster                                 |
| pickle_pure_python   | 201 us                                                 | 193 us: 1.04x faster                                  |
| unpickle_pure_python | 159 us                                                 | 154 us: 1.03x faster                                  |
| xml_etree_parse      | 108 ms                                                 | 109 ms: 1.01x slower                                  |
| pickle               | 7.15 us                                                | 7.33 us: 1.03x slower                                 |
| pickle_list          | 2.81 us                                                | 2.90 us: 1.03x slower                                 |
| tomli_loads          | 1.47 sec                                               | 1.53 sec: 1.05x slower                                |
| xml_etree_iterparse  | 70.1 ms                                                | 75.0 ms: 1.07x slower                                 |
| json_loads           | 16.1 us                                                | 17.5 us: 1.09x slower                                 |
| xml_etree_process    | 35.1 ms                                                | 39.0 ms: 1.11x slower                                 |
| xml_etree_generate   | 48.3 ms                                                | 56.1 ms: 1.16x slower                                 |
| unpickle_list        | 2.65 us                                                | 3.12 us: 1.18x slower                                 |
| Geometric mean       | (ref)                                                  | 1.03x slower                                          |

Benchmark hidden because not significant (1): pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230930-darwin-arm64-python-main-3.13.0a0-53eb9a6 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup_no_site | 10.2 ms                                                | 9.35 ms: 1.09x faster                                 |
| python_startup         | 12.4 ms                                                | 12.0 ms: 1.04x faster                                 |
| Geometric mean         | (ref)                                                  | 1.06x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230930-darwin-arm64-python-main-3.13.0a0-53eb9a6 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 8.53 ms                                                | 7.23 ms: 1.18x faster                                 |

All benchmarks:
===============

| Benchmark                | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230930-darwin-arm64-python-main-3.13.0a0-53eb9a6 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 93.0 us: 3.61x faster                                 |
| asyncio_tcp              | 651 ms                                                 | 433 ms: 1.50x faster                                  |
| unpack_sequence          | 34.1 ns                                                | 26.2 ns: 1.30x faster                                 |
| coverage                 | 58.4 ms                                                | 46.2 ms: 1.26x faster                                 |
| chaos                    | 49.4 ms                                                | 39.7 ms: 1.25x faster                                 |
| sqlglot_parse            | 959 us                                                 | 792 us: 1.21x faster                                  |
| raytrace                 | 207 ms                                                 | 171 ms: 1.21x faster                                  |
| deltablue                | 2.81 ms                                                | 2.34 ms: 1.20x faster                                 |
| mako                     | 8.53 ms                                                | 7.23 ms: 1.18x faster                                 |
| sqlglot_transpile        | 1.12 ms                                                | 963 us: 1.17x faster                                  |
| generators               | 28.8 ms                                                | 24.7 ms: 1.16x faster                                 |
| json_dumps               | 7.63 ms                                                | 6.67 ms: 1.14x faster                                 |
| async_tree_none          | 286 ms                                                 | 250 ms: 1.14x faster                                  |
| asyncio_tcp_ssl          | 1.44 sec                                               | 1.27 sec: 1.13x faster                                |
| crypto_pyaes             | 51.7 ms                                                | 46.4 ms: 1.11x faster                                 |
| deepcopy_memo            | 26.3 us                                                | 23.9 us: 1.10x faster                                 |
| comprehensions           | 16.1 us                                                | 14.8 us: 1.09x faster                                 |
| regex_dna                | 152 ms                                                 | 140 ms: 1.09x faster                                  |
| python_startup_no_site   | 10.2 ms                                                | 9.35 ms: 1.09x faster                                 |
| scimark_sparse_mat_mult  | 3.19 ms                                                | 3.00 ms: 1.06x faster                                 |
| unpickle                 | 9.67 us                                                | 9.11 us: 1.06x faster                                 |
| scimark_lu               | 73.3 ms                                                | 69.5 ms: 1.05x faster                                 |
| go                       | 109 ms                                                 | 103 ms: 1.05x faster                                  |
| scimark_monte_carlo      | 46.5 ms                                                | 44.2 ms: 1.05x faster                                 |
| spectral_norm            | 72.6 ms                                                | 69.1 ms: 1.05x faster                                 |
| regex_effbot             | 2.63 ms                                                | 2.51 ms: 1.05x faster                                 |
| nqueens                  | 59.8 ms                                                | 57.2 ms: 1.04x faster                                 |
| pickle_pure_python       | 201 us                                                 | 193 us: 1.04x faster                                  |
| python_startup           | 12.4 ms                                                | 12.0 ms: 1.04x faster                                 |
| richards_super           | 39.2 ms                                                | 37.9 ms: 1.04x faster                                 |
| unpickle_pure_python     | 159 us                                                 | 154 us: 1.03x faster                                  |
| async_tree_memoization   | 336 ms                                                 | 326 ms: 1.03x faster                                  |
| scimark_fft              | 200 ms                                                 | 194 ms: 1.03x faster                                  |
| async_tree_cpu_io_mixed  | 533 ms                                                 | 521 ms: 1.02x faster                                  |
| hexiom                   | 4.72 ms                                                | 4.61 ms: 1.02x faster                                 |
| mypy2                    | 195 ms                                                 | 191 ms: 1.02x faster                                  |
| pycparser                | 698 ms                                                 | 683 ms: 1.02x faster                                  |
| create_gc_cycles         | 716 us                                                 | 703 us: 1.02x faster                                  |
| async_tree_io            | 704 ms                                                 | 696 ms: 1.01x faster                                  |
| regex_compile            | 76.7 ms                                                | 75.8 ms: 1.01x faster                                 |
| logging_silent           | 68.1 ns                                                | 67.4 ns: 1.01x faster                                 |
| gc_traversal             | 2.42 ms                                                | 2.40 ms: 1.01x faster                                 |
| deepcopy                 | 223 us                                                 | 222 us: 1.00x faster                                  |
| regex_v8                 | 16.1 ms                                                | 16.1 ms: 1.00x slower                                 |
| pidigits                 | 281 ms                                                 | 281 ms: 1.00x slower                                  |
| float                    | 53.0 ms                                                | 53.4 ms: 1.01x slower                                 |
| nbody                    | 65.6 ms                                                | 66.1 ms: 1.01x slower                                 |
| xml_etree_parse          | 108 ms                                                 | 109 ms: 1.01x slower                                  |
| docutils                 | 1.47 sec                                               | 1.49 sec: 1.01x slower                                |
| bench_thread_pool        | 474 us                                                 | 483 us: 1.02x slower                                  |
| logging_simple           | 3.55 us                                                | 3.64 us: 1.02x slower                                 |
| pickle                   | 7.15 us                                                | 7.33 us: 1.03x slower                                 |
| pickle_list              | 2.81 us                                                | 2.90 us: 1.03x slower                                 |
| logging_format           | 3.78 us                                                | 3.92 us: 1.04x slower                                 |
| deepcopy_reduce          | 1.91 us                                                | 1.98 us: 1.04x slower                                 |
| mdp                      | 1.55 sec                                               | 1.60 sec: 1.04x slower                                |
| tomli_loads              | 1.47 sec                                               | 1.53 sec: 1.05x slower                                |
| pprint_pformat           | 954 ms                                                 | 1.01 sec: 1.06x slower                                |
| bench_mp_pool            | 43.9 ms                                                | 46.9 ms: 1.07x slower                                 |
| richards                 | 32.2 ms                                                | 34.4 ms: 1.07x slower                                 |
| xml_etree_iterparse      | 70.1 ms                                                | 75.0 ms: 1.07x slower                                 |
| sqlglot_normalize        | 171 ms                                                 | 183 ms: 1.07x slower                                  |
| pprint_safe_repr         | 466 ms                                                 | 500 ms: 1.07x slower                                  |
| pyflate                  | 310 ms                                                 | 335 ms: 1.08x slower                                  |
| json                     | 2.78 ms                                                | 3.01 ms: 1.08x slower                                 |
| fannkuch                 | 261 ms                                                 | 285 ms: 1.09x slower                                  |
| json_loads               | 16.1 us                                                | 17.5 us: 1.09x slower                                 |
| sqlglot_optimize         | 31.1 ms                                                | 34.2 ms: 1.10x slower                                 |
| xml_etree_process        | 35.1 ms                                                | 39.0 ms: 1.11x slower                                 |
| xml_etree_generate       | 48.3 ms                                                | 56.1 ms: 1.16x slower                                 |
| unpickle_list            | 2.65 us                                                | 3.12 us: 1.18x slower                                 |
| pathlib                  | 27.2 ms                                                | 33.6 ms: 1.24x slower                                 |
| scimark_sor              | 82.6 ms                                                | 103 ms: 1.24x slower                                  |
| sqlite_synth             | 1.27 us                                                | 1.59 us: 1.25x slower                                 |
| telco                    | 3.41 ms                                                | 4.62 ms: 1.36x slower                                 |
| async_generators         | 196 ms                                                 | 295 ms: 1.51x slower                                  |
| Geometric mean           | (ref)                                                  | 1.03x faster                                          |

Benchmark hidden because not significant (5): tornado_http, coroutines, dulwich_log, pickle_dict, meteor_contest
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 70.02% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
