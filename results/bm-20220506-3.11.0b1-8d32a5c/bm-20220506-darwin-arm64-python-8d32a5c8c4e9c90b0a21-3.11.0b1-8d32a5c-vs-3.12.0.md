
# Results vs. 3.12.0

- fork: python
- ref: 8d32a5c8c4e9c90b0a21
- machine: darwin-arm64
- commit hash: 8d32a5c
- commit date: 2022-05-06
- overall geometric mean: 1.01x faster
- HPT reliability: 99.92%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20220506-darwin-arm64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 170 ms                                                              | 152 ms: 1.11x faster                                                  |
| chameleon      | 4.51 ms                                                             | 4.32 ms: 1.05x faster                                                 |
| docutils       | 1.53 sec                                                            | 1.39 sec: 1.10x faster                                                |
| Geometric mean | (ref)                                                               | 1.07x faster                                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20220506-darwin-arm64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_cpu_io_mixed    | 520 ms                                                              | 514 ms: 1.01x faster                                                  |
| async_tree_io              | 659 ms                                                              | 690 ms: 1.05x slower                                                  |
| async_tree_none            | 258 ms                                                              | 277 ms: 1.07x slower                                                  |
| async_tree_io_tg           | 664 ms                                                              | 737 ms: 1.11x slower                                                  |
| async_tree_cpu_io_mixed_tg | 530 ms                                                              | 607 ms: 1.14x slower                                                  |
| async_tree_memoization     | 306 ms                                                              | 353 ms: 1.15x slower                                                  |
| async_tree_none_tg         | 252 ms                                                              | 332 ms: 1.32x slower                                                  |
| async_tree_memoization_tg  | 316 ms                                                              | 434 ms: 1.37x slower                                                  |
| Geometric mean             | (ref)                                                               | 1.14x slower                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20220506-darwin-arm64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 58.0 ms                                                             | 53.3 ms: 1.09x faster                                                 |
| nbody          | 68.8 ms                                                             | 65.6 ms: 1.05x faster                                                 |
| pidigits       | 282 ms                                                              | 281 ms: 1.01x faster                                                  |
| Geometric mean | (ref)                                                               | 1.05x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20220506-darwin-arm64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_effbot   | 2.58 ms                                                             | 2.26 ms: 1.14x faster                                                 |
| regex_dna      | 152 ms                                                              | 144 ms: 1.05x faster                                                  |
| regex_compile  | 75.8 ms                                                             | 73.1 ms: 1.04x faster                                                 |
| regex_v8       | 15.6 ms                                                             | 15.8 ms: 1.01x slower                                                 |
| Geometric mean | (ref)                                                               | 1.05x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20220506-darwin-arm64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| xml_etree_generate   | 55.8 ms                                                             | 46.9 ms: 1.19x faster                                                 |
| unpickle_list        | 3.20 us                                                             | 2.77 us: 1.16x faster                                                 |
| pickle_list          | 2.89 us                                                             | 2.55 us: 1.13x faster                                                 |
| xml_etree_process    | 38.6 ms                                                             | 34.2 ms: 1.13x faster                                                 |
| json_loads           | 17.3 us                                                             | 15.5 us: 1.12x faster                                                 |
| pickle_dict          | 18.1 us                                                             | 16.2 us: 1.12x faster                                                 |
| unpickle             | 9.26 us                                                             | 8.32 us: 1.11x faster                                                 |
| xml_etree_iterparse  | 74.2 ms                                                             | 67.2 ms: 1.10x faster                                                 |
| xml_etree_parse      | 106 ms                                                              | 97.3 ms: 1.09x faster                                                 |
| tomli_loads          | 1.40 sec                                                            | 1.31 sec: 1.07x faster                                                |
| pickle               | 7.35 us                                                             | 6.98 us: 1.05x faster                                                 |
| pickle_pure_python   | 189 us                                                              | 196 us: 1.04x slower                                                  |
| unpickle_pure_python | 144 us                                                              | 152 us: 1.05x slower                                                  |
| json_dumps           | 6.48 ms                                                             | 7.57 ms: 1.17x slower                                                 |
| Geometric mean       | (ref)                                                               | 1.07x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20220506-darwin-arm64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 9.90 ms                                                             | 9.27 ms: 1.07x faster                                                 |
| python_startup         | 12.1 ms                                                             | 11.4 ms: 1.06x faster                                                 |
| Geometric mean         | (ref)                                                               | 1.07x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20220506-darwin-arm64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|-----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| django_template | 21.8 ms                                                             | 19.6 ms: 1.11x faster                                                 |
| mako            | 7.52 ms                                                             | 8.18 ms: 1.09x slower                                                 |
| Geometric mean  | (ref)                                                               | 1.01x faster                                                          |

All benchmarks:
===============

| Benchmark                  | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20220506-darwin-arm64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_generators           | 306 ms                                                              | 190 ms: 1.61x faster                                                  |
| mypy2                      | 256 ms                                                              | 187 ms: 1.37x faster                                                  |
| raytrace                   | 245 ms                                                              | 203 ms: 1.21x faster                                                  |
| sqlite_synth               | 1.60 us                                                             | 1.33 us: 1.21x faster                                                 |
| scimark_sor                | 93.8 ms                                                             | 78.2 ms: 1.20x faster                                                 |
| telco                      | 3.79 ms                                                             | 3.18 ms: 1.19x faster                                                 |
| xml_etree_generate         | 55.8 ms                                                             | 46.9 ms: 1.19x faster                                                 |
| unpickle_list              | 3.20 us                                                             | 2.77 us: 1.16x faster                                                 |
| pyflate                    | 328 ms                                                              | 286 ms: 1.15x faster                                                  |
| regex_effbot               | 2.58 ms                                                             | 2.26 ms: 1.14x faster                                                 |
| scimark_monte_carlo        | 50.0 ms                                                             | 44.1 ms: 1.13x faster                                                 |
| pickle_list                | 2.89 us                                                             | 2.55 us: 1.13x faster                                                 |
| sqlglot_normalize          | 186 ms                                                              | 164 ms: 1.13x faster                                                  |
| xml_etree_process          | 38.6 ms                                                             | 34.2 ms: 1.13x faster                                                 |
| sqlglot_optimize           | 34.3 ms                                                             | 30.5 ms: 1.13x faster                                                 |
| json                       | 3.11 ms                                                             | 2.77 ms: 1.13x faster                                                 |
| bench_mp_pool              | 46.8 ms                                                             | 41.7 ms: 1.12x faster                                                 |
| json_loads                 | 17.3 us                                                             | 15.5 us: 1.12x faster                                                 |
| pickle_dict                | 18.1 us                                                             | 16.2 us: 1.12x faster                                                 |
| 2to3                       | 170 ms                                                              | 152 ms: 1.11x faster                                                  |
| django_template            | 21.8 ms                                                             | 19.6 ms: 1.11x faster                                                 |
| unpickle                   | 9.26 us                                                             | 8.32 us: 1.11x faster                                                 |
| xml_etree_iterparse        | 74.2 ms                                                             | 67.2 ms: 1.10x faster                                                 |
| docutils                   | 1.53 sec                                                            | 1.39 sec: 1.10x faster                                                |
| sqlalchemy_declarative     | 65.4 ms                                                             | 59.7 ms: 1.10x faster                                                 |
| nqueens                    | 59.6 ms                                                             | 54.5 ms: 1.10x faster                                                 |
| spectral_norm              | 74.6 ms                                                             | 68.2 ms: 1.09x faster                                                 |
| xml_etree_parse            | 106 ms                                                              | 97.3 ms: 1.09x faster                                                 |
| float                      | 58.0 ms                                                             | 53.3 ms: 1.09x faster                                                 |
| logging_simple             | 3.70 us                                                             | 3.41 us: 1.09x faster                                                 |
| scimark_fft                | 198 ms                                                              | 182 ms: 1.09x faster                                                  |
| crypto_pyaes               | 51.8 ms                                                             | 47.8 ms: 1.08x faster                                                 |
| logging_format             | 3.98 us                                                             | 3.68 us: 1.08x faster                                                 |
| coroutines                 | 18.2 ms                                                             | 16.9 ms: 1.08x faster                                                 |
| sympy_expand               | 250 ms                                                              | 232 ms: 1.08x faster                                                  |
| python_startup_no_site     | 9.90 ms                                                             | 9.27 ms: 1.07x faster                                                 |
| aiohttp                    | 1.18 ms                                                             | 1.11 ms: 1.07x faster                                                 |
| tomli_loads                | 1.40 sec                                                            | 1.31 sec: 1.07x faster                                                |
| scimark_sparse_mat_mult    | 3.14 ms                                                             | 2.95 ms: 1.07x faster                                                 |
| python_startup             | 12.1 ms                                                             | 11.4 ms: 1.06x faster                                                 |
| fannkuch                   | 262 ms                                                              | 247 ms: 1.06x faster                                                  |
| sympy_str                  | 151 ms                                                              | 143 ms: 1.06x faster                                                  |
| pathlib                    | 24.4 ms                                                             | 23.1 ms: 1.05x faster                                                 |
| regex_dna                  | 152 ms                                                              | 144 ms: 1.05x faster                                                  |
| pickle                     | 7.35 us                                                             | 6.98 us: 1.05x faster                                                 |
| deepcopy_reduce            | 2.03 us                                                             | 1.93 us: 1.05x faster                                                 |
| nbody                      | 68.8 ms                                                             | 65.6 ms: 1.05x faster                                                 |
| bench_thread_pool          | 503 us                                                              | 480 us: 1.05x faster                                                  |
| chameleon                  | 4.51 ms                                                             | 4.32 ms: 1.05x faster                                                 |
| scimark_lu                 | 71.4 ms                                                             | 68.4 ms: 1.04x faster                                                 |
| gunicorn                   | 1.22 ms                                                             | 1.18 ms: 1.04x faster                                                 |
| regex_compile              | 75.8 ms                                                             | 73.1 ms: 1.04x faster                                                 |
| dulwich_log                | 29.8 ms                                                             | 28.9 ms: 1.03x faster                                                 |
| logging_silent             | 67.8 ns                                                             | 65.8 ns: 1.03x faster                                                 |
| go                         | 106 ms                                                              | 104 ms: 1.02x faster                                                  |
| pprint_safe_repr           | 492 ms                                                              | 482 ms: 1.02x faster                                                  |
| pprint_pformat             | 1.00 sec                                                            | 985 ms: 1.02x faster                                                  |
| sympy_integrate            | 11.3 ms                                                             | 11.1 ms: 1.02x faster                                                 |
| dask                       | 224 ms                                                              | 220 ms: 1.02x faster                                                  |
| sympy_sum                  | 79.1 ms                                                             | 78.1 ms: 1.01x faster                                                 |
| pycparser                  | 667 ms                                                              | 659 ms: 1.01x faster                                                  |
| async_tree_cpu_io_mixed    | 520 ms                                                              | 514 ms: 1.01x faster                                                  |
| gc_traversal               | 2.40 ms                                                             | 2.38 ms: 1.01x faster                                                 |
| meteor_contest             | 72.9 ms                                                             | 72.5 ms: 1.01x faster                                                 |
| pidigits                   | 282 ms                                                              | 281 ms: 1.01x faster                                                  |
| asyncio_websockets         | 408 ms                                                              | 407 ms: 1.00x faster                                                  |
| richards                   | 31.0 ms                                                             | 31.1 ms: 1.00x slower                                                 |
| regex_v8                   | 15.6 ms                                                             | 15.8 ms: 1.01x slower                                                 |
| deepcopy                   | 224 us                                                              | 228 us: 1.02x slower                                                  |
| create_gc_cycles           | 702 us                                                              | 715 us: 1.02x slower                                                  |
| sqlalchemy_imperative      | 6.92 ms                                                             | 7.14 ms: 1.03x slower                                                 |
| mdp                        | 1.67 sec                                                            | 1.73 sec: 1.04x slower                                                |
| pickle_pure_python         | 189 us                                                              | 196 us: 1.04x slower                                                  |
| deltablue                  | 2.59 ms                                                             | 2.71 ms: 1.04x slower                                                 |
| generators                 | 28.6 ms                                                             | 29.9 ms: 1.05x slower                                                 |
| async_tree_io              | 659 ms                                                              | 690 ms: 1.05x slower                                                  |
| unpickle_pure_python       | 144 us                                                              | 152 us: 1.05x slower                                                  |
| async_tree_none            | 258 ms                                                              | 277 ms: 1.07x slower                                                  |
| richards_super             | 34.9 ms                                                             | 37.4 ms: 1.07x slower                                                 |
| chaos                      | 44.6 ms                                                             | 48.2 ms: 1.08x slower                                                 |
| hexiom                     | 4.24 ms                                                             | 4.59 ms: 1.08x slower                                                 |
| comprehensions             | 15.7 us                                                             | 17.1 us: 1.09x slower                                                 |
| mako                       | 7.52 ms                                                             | 8.18 ms: 1.09x slower                                                 |
| async_tree_io_tg           | 664 ms                                                              | 737 ms: 1.11x slower                                                  |
| deepcopy_memo              | 24.6 us                                                             | 27.8 us: 1.13x slower                                                 |
| asyncio_tcp_ssl            | 1.26 sec                                                            | 1.43 sec: 1.14x slower                                                |
| async_tree_cpu_io_mixed_tg | 530 ms                                                              | 607 ms: 1.14x slower                                                  |
| unpack_sequence            | 28.7 ns                                                             | 32.9 ns: 1.15x slower                                                 |
| async_tree_memoization     | 306 ms                                                              | 353 ms: 1.15x slower                                                  |
| json_dumps                 | 6.48 ms                                                             | 7.57 ms: 1.17x slower                                                 |
| sqlglot_transpile          | 1.07 ms                                                             | 1.29 ms: 1.20x slower                                                 |
| sqlglot_parse              | 895 us                                                              | 1.12 ms: 1.26x slower                                                 |
| async_tree_none_tg         | 252 ms                                                              | 332 ms: 1.32x slower                                                  |
| async_tree_memoization_tg  | 316 ms                                                              | 434 ms: 1.37x slower                                                  |
| asyncio_tcp                | 419 ms                                                              | 660 ms: 1.58x slower                                                  |
| coverage                   | 37.8 ms                                                             | 73.6 ms: 1.95x slower                                                 |
| typing_runtime_protocols   | 90.6 us                                                             | 327 us: 3.61x slower                                                  |
| Geometric mean             | (ref)                                                               | 1.01x faster                                                          |

Benchmark hidden because not significant (1): tornado_http
Ignored benchmarks (6) of results/bm-20220506-3.11.0b1-8d32a5c/bm-20220506-darwin-arm64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 99.92% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.01x
