
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: darwin-arm64
- commit hash: 241ce0f
- commit date: 2023-11-11
- overall geometric mean: 1.01x slower \*
- HPT reliability: 99.92%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-darwin-arm64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 171 ms                                                 | 178 ms: 1.04x slower                                           |
| chameleon      | 4.51 ms                                                | 4.74 ms: 1.05x slower                                          |
| docutils       | 1.54 sec                                               | 1.51 sec: 1.02x faster                                         |
| Geometric mean | (ref)                                                  | 1.02x slower                                                   |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-darwin-arm64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none            | 262 ms                                                 | 254 ms: 1.03x faster                                           |
| async_tree_cpu_io_mixed_tg | 535 ms                                                 | 546 ms: 1.02x slower                                           |
| async_tree_io_tg           | 673 ms                                                 | 689 ms: 1.02x slower                                           |
| async_tree_memoization_tg  | 320 ms                                                 | 334 ms: 1.04x slower                                           |
| async_tree_none_tg         | 254 ms                                                 | 268 ms: 1.05x slower                                           |
| async_tree_io              | 669 ms                                                 | 706 ms: 1.06x slower                                           |
| async_tree_memoization     | 309 ms                                                 | 332 ms: 1.08x slower                                           |
| Geometric mean             | (ref)                                                  | 1.03x slower                                                   |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-darwin-arm64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 282 ms                                                 | 282 ms: 1.00x slower                                           |
| float          | 58.1 ms                                                | 58.3 ms: 1.00x slower                                          |
| nbody          | 68.5 ms                                                | 82.2 ms: 1.20x slower                                          |
| Geometric mean | (ref)                                                  | 1.06x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-darwin-arm64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_dna      | 153 ms                                                 | 149 ms: 1.02x faster                                           |
| regex_effbot   | 2.59 ms                                                | 2.56 ms: 1.01x faster                                          |
| regex_compile  | 75.6 ms                                                | 79.0 ms: 1.05x slower                                          |
| regex_v8       | 15.7 ms                                                | 16.9 ms: 1.08x slower                                          |
| Geometric mean | (ref)                                                  | 1.02x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-darwin-arm64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| unpickle_list        | 3.24 us                                                | 3.14 us: 1.03x faster                                          |
| pickle_list          | 2.89 us                                                | 2.85 us: 1.02x faster                                          |
| unpickle             | 9.25 us                                                | 9.11 us: 1.02x faster                                          |
| pickle_dict          | 18.0 us                                                | 17.9 us: 1.01x faster                                          |
| pickle               | 7.42 us                                                | 7.45 us: 1.00x slower                                          |
| xml_etree_parse      | 109 ms                                                 | 111 ms: 1.02x slower                                           |
| xml_etree_iterparse  | 74.6 ms                                                | 76.3 ms: 1.02x slower                                          |
| json_dumps           | 6.46 ms                                                | 6.67 ms: 1.03x slower                                          |
| xml_etree_process    | 38.7 ms                                                | 40.0 ms: 1.03x slower                                          |
| xml_etree_generate   | 55.9 ms                                                | 58.1 ms: 1.04x slower                                          |
| pickle_pure_python   | 188 us                                                 | 200 us: 1.06x slower                                           |
| unpickle_pure_python | 145 us                                                 | 162 us: 1.12x slower                                           |
| Geometric mean       | (ref)                                                  | 1.02x slower                                                   |

Benchmark hidden because not significant (2): json_loads, tomli_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-darwin-arm64-brandtbucher-justin-3.13.0a1+-241ce0f |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 11.9 ms                                                | 11.7 ms: 1.02x faster                                          |
| python_startup_no_site | 9.71 ms                                                | 10.3 ms: 1.06x slower                                          |
| Geometric mean         | (ref)                                                  | 1.02x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-darwin-arm64-brandtbucher-justin-3.13.0a1+-241ce0f |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 7.53 ms                                                | 7.63 ms: 1.01x slower                                          |

All benchmarks:
===============

| Benchmark                  | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-darwin-arm64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| raytrace                   | 246 ms                                                 | 183 ms: 1.34x faster                                           |
| typing_runtime_protocols   | 90.8 us                                                | 76.0 us: 1.19x faster                                          |
| comprehensions             | 15.8 us                                                | 13.2 us: 1.19x faster                                          |
| generators                 | 28.3 ms                                                | 24.4 ms: 1.16x faster                                          |
| sqlglot_parse              | 897 us                                                 | 832 us: 1.08x faster                                           |
| crypto_pyaes               | 52.0 ms                                                | 49.0 ms: 1.06x faster                                          |
| sqlglot_transpile          | 1.08 ms                                                | 1.01 ms: 1.06x faster                                          |
| unpack_sequence            | 28.4 ns                                                | 26.9 ns: 1.06x faster                                          |
| logging_format             | 3.99 us                                                | 3.83 us: 1.04x faster                                          |
| logging_simple             | 3.69 us                                                | 3.55 us: 1.04x faster                                          |
| deepcopy_reduce            | 2.05 us                                                | 1.97 us: 1.04x faster                                          |
| bench_mp_pool              | 46.3 ms                                                | 44.7 ms: 1.03x faster                                          |
| unpickle_list              | 3.24 us                                                | 3.14 us: 1.03x faster                                          |
| async_tree_none            | 262 ms                                                 | 254 ms: 1.03x faster                                           |
| chaos                      | 44.8 ms                                                | 43.5 ms: 1.03x faster                                          |
| scimark_monte_carlo        | 50.1 ms                                                | 48.8 ms: 1.03x faster                                          |
| spectral_norm              | 74.6 ms                                                | 72.8 ms: 1.02x faster                                          |
| regex_dna                  | 153 ms                                                 | 149 ms: 1.02x faster                                           |
| deltablue                  | 2.58 ms                                                | 2.53 ms: 1.02x faster                                          |
| python_startup             | 11.9 ms                                                | 11.7 ms: 1.02x faster                                          |
| docutils                   | 1.54 sec                                               | 1.51 sec: 1.02x faster                                         |
| pickle_list                | 2.89 us                                                | 2.85 us: 1.02x faster                                          |
| unpickle                   | 9.25 us                                                | 9.11 us: 1.02x faster                                          |
| regex_effbot               | 2.59 ms                                                | 2.56 ms: 1.01x faster                                          |
| deepcopy                   | 225 us                                                 | 223 us: 1.01x faster                                           |
| go                         | 107 ms                                                 | 106 ms: 1.01x faster                                           |
| coroutines                 | 18.1 ms                                                | 18.0 ms: 1.01x faster                                          |
| json                       | 3.02 ms                                                | 2.99 ms: 1.01x faster                                          |
| create_gc_cycles           | 704 us                                                 | 699 us: 1.01x faster                                           |
| pickle_dict                | 18.0 us                                                | 17.9 us: 1.01x faster                                          |
| pidigits                   | 282 ms                                                 | 282 ms: 1.00x slower                                           |
| dulwich_log                | 30.4 ms                                                | 30.5 ms: 1.00x slower                                          |
| float                      | 58.1 ms                                                | 58.3 ms: 1.00x slower                                          |
| pickle                     | 7.42 us                                                | 7.45 us: 1.00x slower                                          |
| mdp                        | 1.66 sec                                               | 1.67 sec: 1.01x slower                                         |
| sqlglot_optimize           | 34.7 ms                                                | 35.0 ms: 1.01x slower                                          |
| mako                       | 7.53 ms                                                | 7.63 ms: 1.01x slower                                          |
| xml_etree_parse            | 109 ms                                                 | 111 ms: 1.02x slower                                           |
| pathlib                    | 29.3 ms                                                | 29.8 ms: 1.02x slower                                          |
| pyflate                    | 329 ms                                                 | 335 ms: 1.02x slower                                           |
| bench_thread_pool          | 492 us                                                 | 502 us: 1.02x slower                                           |
| async_tree_cpu_io_mixed_tg | 535 ms                                                 | 546 ms: 1.02x slower                                           |
| async_generators           | 306 ms                                                 | 313 ms: 1.02x slower                                           |
| xml_etree_iterparse        | 74.6 ms                                                | 76.3 ms: 1.02x slower                                          |
| async_tree_io_tg           | 673 ms                                                 | 689 ms: 1.02x slower                                           |
| scimark_sparse_mat_mult    | 3.14 ms                                                | 3.23 ms: 1.03x slower                                          |
| sqlite_synth               | 1.59 us                                                | 1.63 us: 1.03x slower                                          |
| deepcopy_memo              | 24.6 us                                                | 25.3 us: 1.03x slower                                          |
| asyncio_tcp_ssl            | 1.26 sec                                               | 1.29 sec: 1.03x slower                                         |
| json_dumps                 | 6.46 ms                                                | 6.67 ms: 1.03x slower                                          |
| logging_silent             | 68.3 ns                                                | 70.5 ns: 1.03x slower                                          |
| xml_etree_process          | 38.7 ms                                                | 40.0 ms: 1.03x slower                                          |
| xml_etree_generate         | 55.9 ms                                                | 58.1 ms: 1.04x slower                                          |
| nqueens                    | 60.2 ms                                                | 62.7 ms: 1.04x slower                                          |
| 2to3                       | 171 ms                                                 | 178 ms: 1.04x slower                                           |
| async_tree_memoization_tg  | 320 ms                                                 | 334 ms: 1.04x slower                                           |
| regex_compile              | 75.6 ms                                                | 79.0 ms: 1.05x slower                                          |
| pycparser                  | 670 ms                                                 | 702 ms: 1.05x slower                                           |
| meteor_contest             | 73.3 ms                                                | 76.9 ms: 1.05x slower                                          |
| chameleon                  | 4.51 ms                                                | 4.74 ms: 1.05x slower                                          |
| richards_super             | 34.9 ms                                                | 36.7 ms: 1.05x slower                                          |
| scimark_lu                 | 71.5 ms                                                | 75.1 ms: 1.05x slower                                          |
| async_tree_none_tg         | 254 ms                                                 | 268 ms: 1.05x slower                                           |
| async_tree_io              | 669 ms                                                 | 706 ms: 1.06x slower                                           |
| richards                   | 31.1 ms                                                | 32.9 ms: 1.06x slower                                          |
| python_startup_no_site     | 9.71 ms                                                | 10.3 ms: 1.06x slower                                          |
| pickle_pure_python         | 188 us                                                 | 200 us: 1.06x slower                                           |
| async_tree_memoization     | 309 ms                                                 | 332 ms: 1.08x slower                                           |
| scimark_fft                | 198 ms                                                 | 213 ms: 1.08x slower                                           |
| regex_v8                   | 15.7 ms                                                | 16.9 ms: 1.08x slower                                          |
| fannkuch                   | 265 ms                                                 | 293 ms: 1.10x slower                                           |
| unpickle_pure_python       | 145 us                                                 | 162 us: 1.12x slower                                           |
| scimark_sor                | 94.3 ms                                                | 106 ms: 1.13x slower                                           |
| nbody                      | 68.5 ms                                                | 82.2 ms: 1.20x slower                                          |
| hexiom                     | 4.25 ms                                                | 5.11 ms: 1.20x slower                                          |
| telco                      | 3.79 ms                                                | 4.63 ms: 1.22x slower                                          |
| coverage                   | 37.9 ms                                                | 48.0 ms: 1.27x slower                                          |
| Geometric mean             | (ref)                                                  | 1.01x slower                                                   |

Benchmark hidden because not significant (9): json_loads, gc_traversal, asyncio_websockets, sqlglot_normalize, tomli_loads, tornado_http, async_tree_cpu_io_mixed, asyncio_tcp, mypy2
Ignored benchmarks (12) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, pprint_pformat, pprint_safe_repr, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum


# HPT report

- Reliability score: 99.92% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
