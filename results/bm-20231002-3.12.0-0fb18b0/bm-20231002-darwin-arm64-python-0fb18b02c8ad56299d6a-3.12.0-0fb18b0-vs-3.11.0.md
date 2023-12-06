
# Results vs. 3.11.0

- fork: python
- ref: 0fb18b02c8ad56299d6a
- machine: darwin-arm64
- commit hash: 0fb18b0
- commit date: 2023-10-02
- overall geometric mean: 1.02x slower
- HPT reliability: 99.93%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 |
|----------------|:-------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| 2to3           | 154 ms                                                              | 170 ms: 1.11x slower                                                |
| chameleon      | 4.21 ms                                                             | 4.51 ms: 1.07x slower                                               |
| docutils       | 1.43 sec                                                            | 1.53 sec: 1.07x slower                                              |
| Geometric mean | (ref)                                                               | 1.06x slower                                                        |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 |
|----------------------------|:-------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| async_tree_memoization     | 353 ms                                                              | 306 ms: 1.16x faster                                                |
| async_tree_memoization_tg  | 351 ms                                                              | 316 ms: 1.11x faster                                                |
| async_tree_none_tg         | 277 ms                                                              | 252 ms: 1.10x faster                                                |
| async_tree_io_tg           | 723 ms                                                              | 664 ms: 1.09x faster                                                |
| async_tree_none            | 277 ms                                                              | 258 ms: 1.07x faster                                                |
| async_tree_io              | 691 ms                                                              | 659 ms: 1.05x faster                                                |
| async_tree_cpu_io_mixed_tg | 548 ms                                                              | 530 ms: 1.03x faster                                                |
| async_tree_cpu_io_mixed    | 516 ms                                                              | 520 ms: 1.01x slower                                                |
| Geometric mean             | (ref)                                                               | 1.07x faster                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 |
|----------------|:-------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| nbody          | 68.5 ms                                                             | 68.8 ms: 1.00x slower                                               |
| pidigits       | 280 ms                                                              | 282 ms: 1.01x slower                                                |
| float          | 55.1 ms                                                             | 58.0 ms: 1.05x slower                                               |
| Geometric mean | (ref)                                                               | 1.02x slower                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 |
|----------------|:-------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_v8       | 15.4 ms                                                             | 15.6 ms: 1.02x slower                                               |
| regex_dna      | 149 ms                                                              | 152 ms: 1.02x slower                                                |
| regex_compile  | 73.5 ms                                                             | 75.8 ms: 1.03x slower                                               |
| regex_effbot   | 2.45 ms                                                             | 2.58 ms: 1.05x slower                                               |
| Geometric mean | (ref)                                                               | 1.03x slower                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 |
|----------------------|:-------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| json_dumps           | 7.58 ms                                                             | 6.48 ms: 1.17x faster                                               |
| unpickle_pure_python | 162 us                                                              | 144 us: 1.12x faster                                                |
| pickle_pure_python   | 210 us                                                              | 189 us: 1.11x faster                                                |
| pickle               | 7.17 us                                                             | 7.35 us: 1.03x slower                                               |
| tomli_loads          | 1.32 sec                                                            | 1.40 sec: 1.06x slower                                              |
| pickle_dict          | 17.0 us                                                             | 18.1 us: 1.07x slower                                               |
| pickle_list          | 2.68 us                                                             | 2.89 us: 1.08x slower                                               |
| xml_etree_parse      | 97.6 ms                                                             | 106 ms: 1.09x slower                                                |
| xml_etree_iterparse  | 67.5 ms                                                             | 74.2 ms: 1.10x slower                                               |
| unpickle             | 8.35 us                                                             | 9.26 us: 1.11x slower                                               |
| json_loads           | 15.5 us                                                             | 17.3 us: 1.12x slower                                               |
| xml_etree_process    | 34.1 ms                                                             | 38.6 ms: 1.13x slower                                               |
| unpickle_list        | 2.76 us                                                             | 3.20 us: 1.16x slower                                               |
| xml_etree_generate   | 47.1 ms                                                             | 55.8 ms: 1.18x slower                                               |
| Geometric mean       | (ref)                                                               | 1.05x slower                                                        |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 |
|------------------------|:-------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                             | 12.1 ms: 1.05x slower                                               |
| python_startup_no_site | 9.37 ms                                                             | 9.90 ms: 1.06x slower                                               |
| Geometric mean         | (ref)                                                               | 1.06x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 |
|-----------------|:-------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako            | 8.25 ms                                                             | 7.52 ms: 1.10x faster                                               |
| django_template | 19.6 ms                                                             | 21.8 ms: 1.11x slower                                               |
| Geometric mean  | (ref)                                                               | 1.01x slower                                                        |

All benchmarks:
===============

| Benchmark                  | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 |
|----------------------------|:-------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols   | 322 us                                                              | 90.6 us: 3.55x faster                                               |
| asyncio_tcp                | 664 ms                                                              | 419 ms: 1.58x faster                                                |
| json_dumps                 | 7.58 ms                                                             | 6.48 ms: 1.17x faster                                               |
| deepcopy_memo              | 28.7 us                                                             | 24.6 us: 1.17x faster                                               |
| async_tree_memoization     | 353 ms                                                              | 306 ms: 1.16x faster                                                |
| asyncio_tcp_ssl            | 1.43 sec                                                            | 1.26 sec: 1.13x faster                                              |
| unpack_sequence            | 32.3 ns                                                             | 28.7 ns: 1.12x faster                                               |
| unpickle_pure_python       | 162 us                                                              | 144 us: 1.12x faster                                                |
| pickle_pure_python         | 210 us                                                              | 189 us: 1.11x faster                                                |
| async_tree_memoization_tg  | 351 ms                                                              | 316 ms: 1.11x faster                                                |
| mdp                        | 1.84 sec                                                            | 1.67 sec: 1.10x faster                                              |
| async_tree_none_tg         | 277 ms                                                              | 252 ms: 1.10x faster                                                |
| mako                       | 8.25 ms                                                             | 7.52 ms: 1.10x faster                                               |
| coverage                   | 41.4 ms                                                             | 37.8 ms: 1.10x faster                                               |
| async_tree_io_tg           | 723 ms                                                              | 664 ms: 1.09x faster                                                |
| chaos                      | 48.2 ms                                                             | 44.6 ms: 1.08x faster                                               |
| async_tree_none            | 277 ms                                                              | 258 ms: 1.07x faster                                                |
| hexiom                     | 4.55 ms                                                             | 4.24 ms: 1.07x faster                                               |
| sqlalchemy_imperative      | 7.33 ms                                                             | 6.92 ms: 1.06x faster                                               |
| gc_traversal               | 2.53 ms                                                             | 2.40 ms: 1.05x faster                                               |
| richards_super             | 36.7 ms                                                             | 34.9 ms: 1.05x faster                                               |
| async_tree_io              | 691 ms                                                              | 659 ms: 1.05x faster                                                |
| deltablue                  | 2.69 ms                                                             | 2.59 ms: 1.04x faster                                               |
| deepcopy                   | 232 us                                                              | 224 us: 1.03x faster                                                |
| async_tree_cpu_io_mixed_tg | 548 ms                                                              | 530 ms: 1.03x faster                                                |
| meteor_contest             | 75.3 ms                                                             | 72.9 ms: 1.03x faster                                               |
| sympy_sum                  | 80.8 ms                                                             | 79.1 ms: 1.02x faster                                               |
| create_gc_cycles           | 714 us                                                              | 702 us: 1.02x faster                                                |
| generators                 | 29.0 ms                                                             | 28.6 ms: 1.02x faster                                               |
| asyncio_websockets         | 408 ms                                                              | 408 ms: 1.00x slower                                                |
| nbody                      | 68.5 ms                                                             | 68.8 ms: 1.00x slower                                               |
| pidigits                   | 280 ms                                                              | 282 ms: 1.01x slower                                                |
| async_tree_cpu_io_mixed    | 516 ms                                                              | 520 ms: 1.01x slower                                                |
| richards                   | 30.7 ms                                                             | 31.0 ms: 1.01x slower                                               |
| sympy_integrate            | 11.2 ms                                                             | 11.3 ms: 1.01x slower                                               |
| pycparser                  | 658 ms                                                              | 667 ms: 1.01x slower                                                |
| regex_v8                   | 15.4 ms                                                             | 15.6 ms: 1.02x slower                                               |
| regex_dna                  | 149 ms                                                              | 152 ms: 1.02x slower                                                |
| pprint_pformat             | 986 ms                                                              | 1.00 sec: 1.02x slower                                              |
| dulwich_log                | 29.2 ms                                                             | 29.8 ms: 1.02x slower                                               |
| dask                       | 219 ms                                                              | 224 ms: 1.02x slower                                                |
| sqlglot_parse              | 874 us                                                              | 895 us: 1.02x slower                                                |
| pprint_safe_repr           | 480 ms                                                              | 492 ms: 1.02x slower                                                |
| pickle                     | 7.17 us                                                             | 7.35 us: 1.03x slower                                               |
| regex_compile              | 73.5 ms                                                             | 75.8 ms: 1.03x slower                                               |
| sqlglot_transpile          | 1.04 ms                                                             | 1.07 ms: 1.03x slower                                               |
| deepcopy_reduce            | 1.96 us                                                             | 2.03 us: 1.04x slower                                               |
| go                         | 102 ms                                                              | 106 ms: 1.04x slower                                                |
| sympy_str                  | 144 ms                                                              | 151 ms: 1.05x slower                                                |
| scimark_sparse_mat_mult    | 3.00 ms                                                             | 3.14 ms: 1.05x slower                                               |
| gunicorn                   | 1.17 ms                                                             | 1.22 ms: 1.05x slower                                               |
| scimark_lu                 | 67.9 ms                                                             | 71.4 ms: 1.05x slower                                               |
| regex_effbot               | 2.45 ms                                                             | 2.58 ms: 1.05x slower                                               |
| python_startup             | 11.5 ms                                                             | 12.1 ms: 1.05x slower                                               |
| float                      | 55.1 ms                                                             | 58.0 ms: 1.05x slower                                               |
| logging_silent             | 64.3 ns                                                             | 67.8 ns: 1.05x slower                                               |
| python_startup_no_site     | 9.37 ms                                                             | 9.90 ms: 1.06x slower                                               |
| sympy_expand               | 236 ms                                                              | 250 ms: 1.06x slower                                                |
| pathlib                    | 23.0 ms                                                             | 24.4 ms: 1.06x slower                                               |
| tomli_loads                | 1.32 sec                                                            | 1.40 sec: 1.06x slower                                              |
| fannkuch                   | 247 ms                                                              | 262 ms: 1.06x slower                                                |
| scimark_fft                | 186 ms                                                              | 198 ms: 1.06x slower                                                |
| pickle_dict                | 17.0 us                                                             | 18.1 us: 1.07x slower                                               |
| logging_format             | 3.73 us                                                             | 3.98 us: 1.07x slower                                               |
| docutils                   | 1.43 sec                                                            | 1.53 sec: 1.07x slower                                              |
| aiohttp                    | 1.10 ms                                                             | 1.18 ms: 1.07x slower                                               |
| logging_simple             | 3.45 us                                                             | 3.70 us: 1.07x slower                                               |
| chameleon                  | 4.21 ms                                                             | 4.51 ms: 1.07x slower                                               |
| spectral_norm              | 69.4 ms                                                             | 74.6 ms: 1.07x slower                                               |
| comprehensions             | 14.6 us                                                             | 15.7 us: 1.07x slower                                               |
| bench_thread_pool          | 467 us                                                              | 503 us: 1.08x slower                                                |
| pickle_list                | 2.68 us                                                             | 2.89 us: 1.08x slower                                               |
| crypto_pyaes               | 47.9 ms                                                             | 51.8 ms: 1.08x slower                                               |
| sqlalchemy_declarative     | 60.4 ms                                                             | 65.4 ms: 1.08x slower                                               |
| xml_etree_parse            | 97.6 ms                                                             | 106 ms: 1.09x slower                                                |
| scimark_monte_carlo        | 45.7 ms                                                             | 50.0 ms: 1.09x slower                                               |
| nqueens                    | 54.3 ms                                                             | 59.6 ms: 1.10x slower                                               |
| xml_etree_iterparse        | 67.5 ms                                                             | 74.2 ms: 1.10x slower                                               |
| 2to3                       | 154 ms                                                              | 170 ms: 1.11x slower                                                |
| coroutines                 | 16.4 ms                                                             | 18.2 ms: 1.11x slower                                               |
| unpickle                   | 8.35 us                                                             | 9.26 us: 1.11x slower                                               |
| pyflate                    | 295 ms                                                              | 328 ms: 1.11x slower                                                |
| bench_mp_pool              | 42.1 ms                                                             | 46.8 ms: 1.11x slower                                               |
| django_template            | 19.6 ms                                                             | 21.8 ms: 1.11x slower                                               |
| json_loads                 | 15.5 us                                                             | 17.3 us: 1.12x slower                                               |
| json                       | 2.77 ms                                                             | 3.11 ms: 1.12x slower                                               |
| xml_etree_process          | 34.1 ms                                                             | 38.6 ms: 1.13x slower                                               |
| sqlglot_optimize           | 29.6 ms                                                             | 34.3 ms: 1.16x slower                                               |
| sqlglot_normalize          | 160 ms                                                              | 186 ms: 1.16x slower                                                |
| unpickle_list              | 2.76 us                                                             | 3.20 us: 1.16x slower                                               |
| sqlite_synth               | 1.36 us                                                             | 1.60 us: 1.18x slower                                               |
| xml_etree_generate         | 47.1 ms                                                             | 55.8 ms: 1.18x slower                                               |
| raytrace                   | 205 ms                                                              | 245 ms: 1.19x slower                                                |
| telco                      | 3.17 ms                                                             | 3.79 ms: 1.20x slower                                               |
| scimark_sor                | 74.4 ms                                                             | 93.8 ms: 1.26x slower                                               |
| mypy2                      | 187 ms                                                              | 256 ms: 1.37x slower                                                |
| async_generators           | 191 ms                                                              | 306 ms: 1.60x slower                                                |
| Geometric mean             | (ref)                                                               | 1.02x slower                                                        |

Benchmark hidden because not significant (1): tornado_http
Ignored benchmarks (6) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 99.93% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
