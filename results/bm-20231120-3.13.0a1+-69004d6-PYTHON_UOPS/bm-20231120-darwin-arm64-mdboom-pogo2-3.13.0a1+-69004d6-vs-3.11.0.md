
# Results vs. 3.11.0

- fork: mdboom
- ref: pogo2
- machine: darwin-arm64
- commit hash: 69004d6
- commit date: 2023-11-20
- overall geometric mean: 1.10x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.04x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-darwin-arm64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| 2to3           | 155 ms                                                 | 183 ms: 1.18x slower                                    |
| chameleon      | 4.17 ms                                                | 5.06 ms: 1.21x slower                                   |
| docutils       | 1.46 sec                                               | 1.55 sec: 1.06x slower                                  |
| tornado_http   | 71.0 ms                                                | 74.2 ms: 1.05x slower                                   |
| Geometric mean | (ref)                                                  | 1.12x slower                                            |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-darwin-arm64-mdboom-pogo2-3.13.0a1+-69004d6 |
|---------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| async_tree_none           | 282 ms                                                 | 265 ms: 1.06x faster                                    |
| async_tree_memoization    | 361 ms                                                 | 342 ms: 1.06x faster                                    |
| async_tree_io_tg          | 734 ms                                                 | 702 ms: 1.05x faster                                    |
| async_tree_memoization_tg | 357 ms                                                 | 346 ms: 1.03x faster                                    |
| async_tree_none_tg        | 280 ms                                                 | 278 ms: 1.01x faster                                    |
| async_tree_io             | 705 ms                                                 | 719 ms: 1.02x slower                                    |
| async_tree_cpu_io_mixed   | 522 ms                                                 | 535 ms: 1.03x slower                                    |
| Geometric mean            | (ref)                                                  | 1.02x faster                                            |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-darwin-arm64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| pidigits       | 281 ms                                                 | 283 ms: 1.01x slower                                    |
| float          | 55.4 ms                                                | 72.9 ms: 1.32x slower                                   |
| nbody          | 68.7 ms                                                | 97.7 ms: 1.42x slower                                   |
| Geometric mean | (ref)                                                  | 1.24x slower                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-darwin-arm64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_effbot   | 2.46 ms                                                | 2.56 ms: 1.04x slower                                   |
| regex_v8       | 15.3 ms                                                | 17.0 ms: 1.11x slower                                   |
| regex_compile  | 73.9 ms                                                | 90.8 ms: 1.23x slower                                   |
| Geometric mean | (ref)                                                  | 1.09x slower                                            |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-darwin-arm64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| json_dumps           | 7.58 ms                                                | 6.62 ms: 1.14x faster                                   |
| pickle_pure_python   | 211 us                                                 | 204 us: 1.03x faster                                    |
| pickle               | 7.22 us                                                | 7.34 us: 1.02x slower                                   |
| pickle_dict          | 17.0 us                                                | 17.9 us: 1.05x slower                                   |
| unpickle_pure_python | 163 us                                                 | 175 us: 1.07x slower                                    |
| unpickle             | 8.32 us                                                | 9.08 us: 1.09x slower                                   |
| json_loads           | 15.8 us                                                | 17.2 us: 1.09x slower                                   |
| pickle_list          | 2.67 us                                                | 2.98 us: 1.12x slower                                   |
| unpickle_list        | 2.77 us                                                | 3.15 us: 1.14x slower                                   |
| xml_etree_iterparse  | 68.2 ms                                                | 82.9 ms: 1.22x slower                                   |
| xml_etree_process    | 34.0 ms                                                | 42.7 ms: 1.26x slower                                   |
| xml_etree_generate   | 46.8 ms                                                | 62.3 ms: 1.33x slower                                   |
| tomli_loads          | 1.30 sec                                               | 1.81 sec: 1.39x slower                                  |
| Geometric mean       | (ref)                                                  | 1.11x slower                                            |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-darwin-arm64-mdboom-pogo2-3.13.0a1+-69004d6 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| python_startup         | 11.4 ms                                                | 12.2 ms: 1.07x slower                                   |
| python_startup_no_site | 9.15 ms                                                | 10.7 ms: 1.17x slower                                   |
| Geometric mean         | (ref)                                                  | 1.12x slower                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-darwin-arm64-mdboom-pogo2-3.13.0a1+-69004d6 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------:|
| mako      | 8.22 ms                                                | 10.7 ms: 1.30x slower                                   |

All benchmarks:
===============

| Benchmark                 | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-darwin-arm64-mdboom-pogo2-3.13.0a1+-69004d6 |
|---------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| typing_runtime_protocols  | 323 us                                                 | 80.6 us: 4.00x faster                                   |
| asyncio_tcp               | 650 ms                                                 | 452 ms: 1.44x faster                                    |
| asyncio_websockets        | 544 ms                                                 | 409 ms: 1.33x faster                                    |
| pathlib                   | 28.5 ms                                                | 23.9 ms: 1.20x faster                                   |
| json_dumps                | 7.58 ms                                                | 6.62 ms: 1.14x faster                                   |
| generators                | 29.2 ms                                                | 25.5 ms: 1.14x faster                                   |
| unpack_sequence           | 32.3 ns                                                | 28.2 ns: 1.14x faster                                   |
| asyncio_tcp_ssl           | 1.44 sec                                               | 1.30 sec: 1.11x faster                                  |
| deepcopy_memo             | 28.9 us                                                | 27.1 us: 1.07x faster                                   |
| async_tree_none           | 282 ms                                                 | 265 ms: 1.06x faster                                    |
| async_tree_memoization    | 361 ms                                                 | 342 ms: 1.06x faster                                    |
| async_tree_io_tg          | 734 ms                                                 | 702 ms: 1.05x faster                                    |
| async_tree_memoization_tg | 357 ms                                                 | 346 ms: 1.03x faster                                    |
| pickle_pure_python        | 211 us                                                 | 204 us: 1.03x faster                                    |
| create_gc_cycles          | 715 us                                                 | 699 us: 1.02x faster                                    |
| async_tree_none_tg        | 280 ms                                                 | 278 ms: 1.01x faster                                    |
| deepcopy                  | 233 us                                                 | 234 us: 1.00x slower                                    |
| gc_traversal              | 2.39 ms                                                | 2.40 ms: 1.00x slower                                   |
| sqlglot_parse             | 886 us                                                 | 892 us: 1.01x slower                                    |
| pidigits                  | 281 ms                                                 | 283 ms: 1.01x slower                                    |
| pickle                    | 7.22 us                                                | 7.34 us: 1.02x slower                                   |
| async_tree_io             | 705 ms                                                 | 719 ms: 1.02x slower                                    |
| dulwich_log               | 29.9 ms                                                | 30.5 ms: 1.02x slower                                   |
| async_tree_cpu_io_mixed   | 522 ms                                                 | 535 ms: 1.03x slower                                    |
| dask                      | 224 ms                                                 | 231 ms: 1.03x slower                                    |
| raytrace                  | 200 ms                                                 | 207 ms: 1.03x slower                                    |
| sqlglot_transpile         | 1.05 ms                                                | 1.08 ms: 1.03x slower                                   |
| richards_super            | 36.8 ms                                                | 38.1 ms: 1.03x slower                                   |
| sympy_sum                 | 81.6 ms                                                | 84.8 ms: 1.04x slower                                   |
| regex_effbot              | 2.46 ms                                                | 2.56 ms: 1.04x slower                                   |
| tornado_http              | 71.0 ms                                                | 74.2 ms: 1.05x slower                                   |
| pickle_dict               | 17.0 us                                                | 17.9 us: 1.05x slower                                   |
| deepcopy_reduce           | 1.98 us                                                | 2.09 us: 1.06x slower                                   |
| docutils                  | 1.46 sec                                               | 1.55 sec: 1.06x slower                                  |
| bench_mp_pool             | 41.9 ms                                                | 44.8 ms: 1.07x slower                                   |
| unpickle_pure_python      | 163 us                                                 | 175 us: 1.07x slower                                    |
| python_startup            | 11.4 ms                                                | 12.2 ms: 1.07x slower                                   |
| chaos                     | 48.2 ms                                                | 51.9 ms: 1.08x slower                                   |
| pycparser                 | 667 ms                                                 | 719 ms: 1.08x slower                                    |
| sympy_integrate           | 11.3 ms                                                | 12.2 ms: 1.08x slower                                   |
| unpickle                  | 8.32 us                                                | 9.08 us: 1.09x slower                                   |
| logging_simple            | 3.41 us                                                | 3.72 us: 1.09x slower                                   |
| json_loads                | 15.8 us                                                | 17.2 us: 1.09x slower                                   |
| logging_format            | 3.69 us                                                | 4.03 us: 1.09x slower                                   |
| json                      | 2.77 ms                                                | 3.03 ms: 1.09x slower                                   |
| regex_v8                  | 15.3 ms                                                | 17.0 ms: 1.11x slower                                   |
| sympy_str                 | 144 ms                                                 | 160 ms: 1.11x slower                                    |
| meteor_contest            | 74.9 ms                                                | 83.3 ms: 1.11x slower                                   |
| pickle_list               | 2.67 us                                                | 2.98 us: 1.12x slower                                   |
| richards                  | 30.8 ms                                                | 34.4 ms: 1.12x slower                                   |
| sympy_expand              | 234 ms                                                 | 263 ms: 1.12x slower                                    |
| go                        | 102 ms                                                 | 115 ms: 1.13x slower                                    |
| coroutines                | 16.6 ms                                                | 18.8 ms: 1.14x slower                                   |
| unpickle_list             | 2.77 us                                                | 3.15 us: 1.14x slower                                   |
| coverage                  | 41.4 ms                                                | 47.6 ms: 1.15x slower                                   |
| logging_silent            | 64.5 ns                                                | 74.3 ns: 1.15x slower                                   |
| bench_thread_pool         | 461 us                                                 | 535 us: 1.16x slower                                    |
| scimark_lu                | 67.8 ms                                                | 78.9 ms: 1.16x slower                                   |
| python_startup_no_site    | 9.15 ms                                                | 10.7 ms: 1.17x slower                                   |
| comprehensions            | 14.7 us                                                | 17.3 us: 1.18x slower                                   |
| 2to3                      | 155 ms                                                 | 183 ms: 1.18x slower                                    |
| crypto_pyaes              | 48.1 ms                                                | 58.2 ms: 1.21x slower                                   |
| chameleon                 | 4.17 ms                                                | 5.06 ms: 1.21x slower                                   |
| xml_etree_iterparse       | 68.2 ms                                                | 82.9 ms: 1.22x slower                                   |
| regex_compile             | 73.9 ms                                                | 90.8 ms: 1.23x slower                                   |
| pprint_pformat            | 989 ms                                                 | 1.24 sec: 1.25x slower                                  |
| pprint_safe_repr          | 479 ms                                                 | 601 ms: 1.25x slower                                    |
| xml_etree_process         | 34.0 ms                                                | 42.7 ms: 1.26x slower                                   |
| sqlglot_normalize         | 160 ms                                                 | 203 ms: 1.27x slower                                    |
| sqlite_synth              | 1.35 us                                                | 1.72 us: 1.27x slower                                   |
| sqlglot_optimize          | 29.6 ms                                                | 38.2 ms: 1.29x slower                                   |
| mako                      | 8.22 ms                                                | 10.7 ms: 1.30x slower                                   |
| pyflate                   | 297 ms                                                 | 389 ms: 1.31x slower                                    |
| scimark_monte_carlo       | 47.1 ms                                                | 61.9 ms: 1.32x slower                                   |
| float                     | 55.4 ms                                                | 72.9 ms: 1.32x slower                                   |
| xml_etree_generate        | 46.8 ms                                                | 62.3 ms: 1.33x slower                                   |
| nqueens                   | 54.6 ms                                                | 73.2 ms: 1.34x slower                                   |
| tomli_loads               | 1.30 sec                                               | 1.81 sec: 1.39x slower                                  |
| mypy2                     | 191 ms                                                 | 266 ms: 1.39x slower                                    |
| nbody                     | 68.7 ms                                                | 97.7 ms: 1.42x slower                                   |
| deltablue                 | 2.70 ms                                                | 3.84 ms: 1.43x slower                                   |
| hexiom                    | 4.55 ms                                                | 6.61 ms: 1.45x slower                                   |
| scimark_sor               | 75.2 ms                                                | 110 ms: 1.46x slower                                    |
| scimark_sparse_mat_mult   | 3.01 ms                                                | 4.39 ms: 1.46x slower                                   |
| fannkuch                  | 247 ms                                                 | 363 ms: 1.47x slower                                    |
| scimark_fft               | 187 ms                                                 | 279 ms: 1.49x slower                                    |
| telco                     | 3.17 ms                                                | 4.89 ms: 1.54x slower                                   |
| async_generators          | 192 ms                                                 | 314 ms: 1.63x slower                                    |
| spectral_norm             | 69.7 ms                                                | 115 ms: 1.65x slower                                    |
| Geometric mean            | (ref)                                                  | 1.10x slower                                            |

Benchmark hidden because not significant (4): mdp, async_tree_cpu_io_mixed_tg, xml_etree_parse, regex_dna
Ignored benchmarks (11) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.06x
- 95% likely to have a slowdown of 1.06x
- 99% likely to have a slowdown of 1.04x
