
# Results vs. 3.12.0

- fork: python
- ref: 2e49bd06c5ffab7d1540
- machine: darwin-arm64
- commit hash: 2e49bd0
- commit date: 2022-04-05
- overall geometric mean: 1.02x slower
- HPT reliability: 97.60%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20220405-darwin-arm64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 170 ms                                                              | 156 ms: 1.09x faster                                                  |
| chameleon      | 4.51 ms                                                             | 4.32 ms: 1.05x faster                                                 |
| docutils       | 1.53 sec                                                            | 1.40 sec: 1.10x faster                                                |
| Geometric mean | (ref)                                                               | 1.06x faster                                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20220405-darwin-arm64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|----------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_io              | 659 ms                                                              | 693 ms: 1.05x slower                                                  |
| async_tree_none            | 258 ms                                                              | 277 ms: 1.07x slower                                                  |
| async_tree_io_tg           | 664 ms                                                              | 748 ms: 1.13x slower                                                  |
| async_tree_cpu_io_mixed_tg | 530 ms                                                              | 611 ms: 1.15x slower                                                  |
| async_tree_memoization     | 306 ms                                                              | 361 ms: 1.18x slower                                                  |
| async_tree_none_tg         | 252 ms                                                              | 338 ms: 1.34x slower                                                  |
| async_tree_memoization_tg  | 316 ms                                                              | 436 ms: 1.38x slower                                                  |
| Geometric mean             | (ref)                                                               | 1.16x slower                                                          |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20220405-darwin-arm64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 58.0 ms                                                             | 49.9 ms: 1.16x faster                                                 |
| nbody          | 68.8 ms                                                             | 67.4 ms: 1.02x faster                                                 |
| pidigits       | 282 ms                                                              | 280 ms: 1.01x faster                                                  |
| Geometric mean | (ref)                                                               | 1.06x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20220405-darwin-arm64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_effbot   | 2.58 ms                                                             | 2.07 ms: 1.24x faster                                                 |
| regex_compile  | 75.8 ms                                                             | 73.7 ms: 1.03x faster                                                 |
| regex_dna      | 152 ms                                                              | 175 ms: 1.15x slower                                                  |
| regex_v8       | 15.6 ms                                                             | 19.3 ms: 1.24x slower                                                 |
| Geometric mean | (ref)                                                               | 1.03x slower                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20220405-darwin-arm64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|----------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| xml_etree_generate   | 55.8 ms                                                             | 47.0 ms: 1.19x faster                                                 |
| json_loads           | 17.3 us                                                             | 14.9 us: 1.16x faster                                                 |
| unpickle_list        | 3.20 us                                                             | 2.80 us: 1.14x faster                                                 |
| xml_etree_process    | 38.6 ms                                                             | 34.6 ms: 1.12x faster                                                 |
| unpickle             | 9.26 us                                                             | 8.31 us: 1.11x faster                                                 |
| xml_etree_iterparse  | 74.2 ms                                                             | 67.4 ms: 1.10x faster                                                 |
| xml_etree_parse      | 106 ms                                                              | 97.0 ms: 1.09x faster                                                 |
| pickle_list          | 2.89 us                                                             | 2.66 us: 1.08x faster                                                 |
| pickle_dict          | 18.1 us                                                             | 17.4 us: 1.04x faster                                                 |
| tomli_loads          | 1.40 sec                                                            | 1.36 sec: 1.03x faster                                                |
| pickle               | 7.35 us                                                             | 7.19 us: 1.02x faster                                                 |
| pickle_pure_python   | 189 us                                                              | 190 us: 1.01x slower                                                  |
| unpickle_pure_python | 144 us                                                              | 149 us: 1.03x slower                                                  |
| json_dumps           | 6.48 ms                                                             | 7.58 ms: 1.17x slower                                                 |
| Geometric mean       | (ref)                                                               | 1.06x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20220405-darwin-arm64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 9.90 ms                                                             | 9.19 ms: 1.08x faster                                                 |
| python_startup         | 12.1 ms                                                             | 11.4 ms: 1.07x faster                                                 |
| Geometric mean         | (ref)                                                               | 1.07x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20220405-darwin-arm64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|-----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| django_template | 21.8 ms                                                             | 20.0 ms: 1.09x faster                                                 |
| mako            | 7.52 ms                                                             | 7.05 ms: 1.07x faster                                                 |
| Geometric mean  | (ref)                                                               | 1.08x faster                                                          |

All benchmarks:
===============

| Benchmark                  | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20220405-darwin-arm64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|----------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_generators           | 306 ms                                                              | 189 ms: 1.62x faster                                                  |
| mypy2                      | 256 ms                                                              | 190 ms: 1.35x faster                                                  |
| sqlite_synth               | 1.60 us                                                             | 1.26 us: 1.27x faster                                                 |
| regex_effbot               | 2.58 ms                                                             | 2.07 ms: 1.24x faster                                                 |
| telco                      | 3.79 ms                                                             | 3.15 ms: 1.20x faster                                                 |
| xml_etree_generate         | 55.8 ms                                                             | 47.0 ms: 1.19x faster                                                 |
| raytrace                   | 245 ms                                                              | 207 ms: 1.19x faster                                                  |
| float                      | 58.0 ms                                                             | 49.9 ms: 1.16x faster                                                 |
| json_loads                 | 17.3 us                                                             | 14.9 us: 1.16x faster                                                 |
| unpickle_list              | 3.20 us                                                             | 2.80 us: 1.14x faster                                                 |
| json                       | 3.11 ms                                                             | 2.75 ms: 1.13x faster                                                 |
| scimark_sor                | 93.8 ms                                                             | 82.8 ms: 1.13x faster                                                 |
| bench_mp_pool              | 46.8 ms                                                             | 41.5 ms: 1.13x faster                                                 |
| scimark_monte_carlo        | 50.0 ms                                                             | 44.6 ms: 1.12x faster                                                 |
| sqlglot_normalize          | 186 ms                                                              | 166 ms: 1.12x faster                                                  |
| sqlglot_optimize           | 34.3 ms                                                             | 30.7 ms: 1.12x faster                                                 |
| xml_etree_process          | 38.6 ms                                                             | 34.6 ms: 1.12x faster                                                 |
| unpickle                   | 9.26 us                                                             | 8.31 us: 1.11x faster                                                 |
| logging_format             | 3.98 us                                                             | 3.58 us: 1.11x faster                                                 |
| deepcopy_reduce            | 2.03 us                                                             | 1.83 us: 1.11x faster                                                 |
| logging_simple             | 3.70 us                                                             | 3.35 us: 1.10x faster                                                 |
| pyflate                    | 328 ms                                                              | 297 ms: 1.10x faster                                                  |
| xml_etree_iterparse        | 74.2 ms                                                             | 67.4 ms: 1.10x faster                                                 |
| docutils                   | 1.53 sec                                                            | 1.40 sec: 1.10x faster                                                |
| xml_etree_parse            | 106 ms                                                              | 97.0 ms: 1.09x faster                                                 |
| django_template            | 21.8 ms                                                             | 20.0 ms: 1.09x faster                                                 |
| 2to3                       | 170 ms                                                              | 156 ms: 1.09x faster                                                  |
| pickle_list                | 2.89 us                                                             | 2.66 us: 1.08x faster                                                 |
| aiohttp                    | 1.18 ms                                                             | 1.09 ms: 1.08x faster                                                 |
| python_startup_no_site     | 9.90 ms                                                             | 9.19 ms: 1.08x faster                                                 |
| sqlalchemy_declarative     | 65.4 ms                                                             | 60.7 ms: 1.08x faster                                                 |
| nqueens                    | 59.6 ms                                                             | 55.8 ms: 1.07x faster                                                 |
| python_startup             | 12.1 ms                                                             | 11.4 ms: 1.07x faster                                                 |
| mako                       | 7.52 ms                                                             | 7.05 ms: 1.07x faster                                                 |
| sympy_expand               | 250 ms                                                              | 234 ms: 1.07x faster                                                  |
| scimark_fft                | 198 ms                                                              | 187 ms: 1.06x faster                                                  |
| pathlib                    | 24.4 ms                                                             | 23.1 ms: 1.06x faster                                                 |
| deepcopy                   | 224 us                                                              | 212 us: 1.06x faster                                                  |
| sympy_str                  | 151 ms                                                              | 144 ms: 1.05x faster                                                  |
| spectral_norm              | 74.6 ms                                                             | 70.9 ms: 1.05x faster                                                 |
| chameleon                  | 4.51 ms                                                             | 4.32 ms: 1.05x faster                                                 |
| pickle_dict                | 18.1 us                                                             | 17.4 us: 1.04x faster                                                 |
| gunicorn                   | 1.22 ms                                                             | 1.18 ms: 1.04x faster                                                 |
| scimark_sparse_mat_mult    | 3.14 ms                                                             | 3.04 ms: 1.03x faster                                                 |
| bench_thread_pool          | 503 us                                                              | 487 us: 1.03x faster                                                  |
| dulwich_log                | 29.8 ms                                                             | 28.9 ms: 1.03x faster                                                 |
| fannkuch                   | 262 ms                                                              | 254 ms: 1.03x faster                                                  |
| regex_compile              | 75.8 ms                                                             | 73.7 ms: 1.03x faster                                                 |
| tomli_loads                | 1.40 sec                                                            | 1.36 sec: 1.03x faster                                                |
| pickle                     | 7.35 us                                                             | 7.19 us: 1.02x faster                                                 |
| nbody                      | 68.8 ms                                                             | 67.4 ms: 1.02x faster                                                 |
| go                         | 106 ms                                                              | 105 ms: 1.02x faster                                                  |
| coroutines                 | 18.2 ms                                                             | 17.9 ms: 1.02x faster                                                 |
| sympy_integrate            | 11.3 ms                                                             | 11.2 ms: 1.01x faster                                                 |
| sympy_sum                  | 79.1 ms                                                             | 78.2 ms: 1.01x faster                                                 |
| pidigits                   | 282 ms                                                              | 280 ms: 1.01x faster                                                  |
| gc_traversal               | 2.40 ms                                                             | 2.38 ms: 1.01x faster                                                 |
| asyncio_websockets         | 408 ms                                                              | 407 ms: 1.00x faster                                                  |
| scimark_lu                 | 71.4 ms                                                             | 71.2 ms: 1.00x faster                                                 |
| create_gc_cycles           | 702 us                                                              | 706 us: 1.01x slower                                                  |
| deepcopy_memo              | 24.6 us                                                             | 24.8 us: 1.01x slower                                                 |
| pickle_pure_python         | 189 us                                                              | 190 us: 1.01x slower                                                  |
| richards                   | 31.0 ms                                                             | 31.3 ms: 1.01x slower                                                 |
| meteor_contest             | 72.9 ms                                                             | 73.9 ms: 1.01x slower                                                 |
| pycparser                  | 667 ms                                                              | 684 ms: 1.02x slower                                                  |
| unpickle_pure_python       | 144 us                                                              | 149 us: 1.03x slower                                                  |
| crypto_pyaes               | 51.8 ms                                                             | 53.4 ms: 1.03x slower                                                 |
| logging_silent             | 67.8 ns                                                             | 70.1 ns: 1.03x slower                                                 |
| deltablue                  | 2.59 ms                                                             | 2.69 ms: 1.04x slower                                                 |
| comprehensions             | 15.7 us                                                             | 16.3 us: 1.04x slower                                                 |
| mdp                        | 1.67 sec                                                            | 1.76 sec: 1.05x slower                                                |
| async_tree_io              | 659 ms                                                              | 693 ms: 1.05x slower                                                  |
| generators                 | 28.6 ms                                                             | 30.1 ms: 1.05x slower                                                 |
| sqlalchemy_imperative      | 6.92 ms                                                             | 7.31 ms: 1.06x slower                                                 |
| async_tree_none            | 258 ms                                                              | 277 ms: 1.07x slower                                                  |
| richards_super             | 34.9 ms                                                             | 37.9 ms: 1.09x slower                                                 |
| chaos                      | 44.6 ms                                                             | 48.7 ms: 1.09x slower                                                 |
| async_tree_io_tg           | 664 ms                                                              | 748 ms: 1.13x slower                                                  |
| asyncio_tcp_ssl            | 1.26 sec                                                            | 1.43 sec: 1.13x slower                                                |
| hexiom                     | 4.24 ms                                                             | 4.85 ms: 1.14x slower                                                 |
| async_tree_cpu_io_mixed_tg | 530 ms                                                              | 611 ms: 1.15x slower                                                  |
| regex_dna                  | 152 ms                                                              | 175 ms: 1.15x slower                                                  |
| json_dumps                 | 6.48 ms                                                             | 7.58 ms: 1.17x slower                                                 |
| unpack_sequence            | 28.7 ns                                                             | 33.7 ns: 1.18x slower                                                 |
| async_tree_memoization     | 306 ms                                                              | 361 ms: 1.18x slower                                                  |
| sqlglot_transpile          | 1.07 ms                                                             | 1.30 ms: 1.21x slower                                                 |
| regex_v8                   | 15.6 ms                                                             | 19.3 ms: 1.24x slower                                                 |
| sqlglot_parse              | 895 us                                                              | 1.15 ms: 1.28x slower                                                 |
| async_tree_none_tg         | 252 ms                                                              | 338 ms: 1.34x slower                                                  |
| async_tree_memoization_tg  | 316 ms                                                              | 436 ms: 1.38x slower                                                  |
| asyncio_tcp                | 419 ms                                                              | 663 ms: 1.58x slower                                                  |
| typing_runtime_protocols   | 90.6 us                                                             | 323 us: 3.56x slower                                                  |
| coverage                   | 37.8 ms                                                             | 392 ms: 10.37x slower                                                 |
| Geometric mean             | (ref)                                                               | 1.02x slower                                                          |

Benchmark hidden because not significant (4): async_tree_cpu_io_mixed, pprint_pformat, tornado_http, pprint_safe_repr
Ignored benchmarks (1) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0.json: dask
Ignored benchmarks (6) of results/bm-20220405-3.11.0a7-2e49bd0/bm-20220405-darwin-arm64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 97.60% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
