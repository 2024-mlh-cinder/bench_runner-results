
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin
- machine: darwin-arm64
- commit hash: 7a7e995
- commit date: 2023-11-15
- overall geometric mean: 1.06x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 155 ms                                                 | 183 ms: 1.18x slower                                           |
| chameleon      | 4.17 ms                                                | 4.92 ms: 1.18x slower                                          |
| docutils       | 1.46 sec                                               | 1.55 sec: 1.07x slower                                         |
| tornado_http   | 71.0 ms                                                | 76.3 ms: 1.08x slower                                          |
| Geometric mean | (ref)                                                  | 1.12x slower                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|---------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none           | 282 ms                                                 | 261 ms: 1.08x faster                                           |
| async_tree_memoization    | 361 ms                                                 | 338 ms: 1.07x faster                                           |
| async_tree_io_tg          | 734 ms                                                 | 700 ms: 1.05x faster                                           |
| async_tree_memoization_tg | 357 ms                                                 | 342 ms: 1.04x faster                                           |
| async_tree_none_tg        | 280 ms                                                 | 275 ms: 1.02x faster                                           |
| async_tree_cpu_io_mixed   | 522 ms                                                 | 539 ms: 1.03x slower                                           |
| async_tree_io             | 705 ms                                                 | 729 ms: 1.03x slower                                           |
| Geometric mean            | (ref)                                                  | 1.02x faster                                                   |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 281 ms                                                 | 283 ms: 1.00x slower                                           |
| float          | 55.4 ms                                                | 60.0 ms: 1.08x slower                                          |
| nbody          | 68.7 ms                                                | 83.5 ms: 1.22x slower                                          |
| Geometric mean | (ref)                                                  | 1.10x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_dna      | 149 ms                                                 | 150 ms: 1.01x slower                                           |
| regex_effbot   | 2.46 ms                                                | 2.58 ms: 1.05x slower                                          |
| regex_v8       | 15.3 ms                                                | 17.0 ms: 1.11x slower                                          |
| regex_compile  | 73.9 ms                                                | 83.2 ms: 1.13x slower                                          |
| Geometric mean | (ref)                                                  | 1.07x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| json_dumps           | 7.58 ms                                                | 6.69 ms: 1.13x faster                                          |
| pickle_pure_python   | 211 us                                                 | 206 us: 1.02x faster                                           |
| pickle               | 7.22 us                                                | 7.51 us: 1.04x slower                                          |
| pickle_dict          | 17.0 us                                                | 18.1 us: 1.06x slower                                          |
| pickle_list          | 2.67 us                                                | 2.89 us: 1.08x slower                                          |
| unpickle_pure_python | 163 us                                                 | 179 us: 1.09x slower                                           |
| unpickle             | 8.32 us                                                | 9.35 us: 1.12x slower                                          |
| json_loads           | 15.8 us                                                | 17.9 us: 1.13x slower                                          |
| tomli_loads          | 1.30 sec                                               | 1.53 sec: 1.18x slower                                         |
| unpickle_list        | 2.77 us                                                | 3.37 us: 1.22x slower                                          |
| xml_etree_iterparse  | 68.2 ms                                                | 88.5 ms: 1.30x slower                                          |
| xml_etree_process    | 34.0 ms                                                | 44.5 ms: 1.31x slower                                          |
| xml_etree_parse      | 107 ms                                                 | 140 ms: 1.31x slower                                           |
| xml_etree_generate   | 46.8 ms                                                | 62.5 ms: 1.33x slower                                          |
| Geometric mean       | (ref)                                                  | 1.14x slower                                                   |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 11.4 ms                                                | 11.9 ms: 1.04x slower                                          |
| python_startup_no_site | 9.15 ms                                                | 10.4 ms: 1.14x slower                                          |
| Geometric mean         | (ref)                                                  | 1.09x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 8.22 ms                                                | 7.96 ms: 1.03x faster                                          |

All benchmarks:
===============

| Benchmark                 | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|---------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols  | 323 us                                                 | 78.3 us: 4.12x faster                                          |
| asyncio_tcp               | 650 ms                                                 | 444 ms: 1.46x faster                                           |
| json_dumps                | 7.58 ms                                                | 6.69 ms: 1.13x faster                                          |
| generators                | 29.2 ms                                                | 26.3 ms: 1.11x faster                                          |
| unpack_sequence           | 32.3 ns                                                | 29.1 ns: 1.11x faster                                          |
| asyncio_tcp_ssl           | 1.44 sec                                               | 1.30 sec: 1.10x faster                                         |
| deepcopy_memo             | 28.9 us                                                | 26.3 us: 1.10x faster                                          |
| async_tree_none           | 282 ms                                                 | 261 ms: 1.08x faster                                           |
| async_tree_memoization    | 361 ms                                                 | 338 ms: 1.07x faster                                           |
| chaos                     | 48.2 ms                                                | 45.2 ms: 1.07x faster                                          |
| sympy_sum                 | 81.6 ms                                                | 77.5 ms: 1.05x faster                                          |
| async_tree_io_tg          | 734 ms                                                 | 700 ms: 1.05x faster                                           |
| comprehensions            | 14.7 us                                                | 14.0 us: 1.05x faster                                          |
| async_tree_memoization_tg | 357 ms                                                 | 342 ms: 1.04x faster                                           |
| raytrace                  | 200 ms                                                 | 193 ms: 1.04x faster                                           |
| mako                      | 8.22 ms                                                | 7.96 ms: 1.03x faster                                          |
| sqlglot_parse             | 886 us                                                 | 858 us: 1.03x faster                                           |
| deltablue                 | 2.70 ms                                                | 2.62 ms: 1.03x faster                                          |
| pickle_pure_python        | 211 us                                                 | 206 us: 1.02x faster                                           |
| async_tree_none_tg        | 280 ms                                                 | 275 ms: 1.02x faster                                           |
| mdp                       | 1.73 sec                                               | 1.72 sec: 1.01x faster                                         |
| create_gc_cycles          | 715 us                                                 | 708 us: 1.01x faster                                           |
| sqlglot_transpile         | 1.05 ms                                                | 1.04 ms: 1.01x faster                                          |
| pidigits                  | 281 ms                                                 | 283 ms: 1.00x slower                                           |
| deepcopy                  | 233 us                                                 | 234 us: 1.01x slower                                           |
| richards_super            | 36.8 ms                                                | 37.1 ms: 1.01x slower                                          |
| regex_dna                 | 149 ms                                                 | 150 ms: 1.01x slower                                           |
| asyncio_websockets        | 544 ms                                                 | 550 ms: 1.01x slower                                           |
| gc_traversal              | 2.39 ms                                                | 2.43 ms: 1.02x slower                                          |
| pathlib                   | 28.5 ms                                                | 29.3 ms: 1.03x slower                                          |
| deepcopy_reduce           | 1.98 us                                                | 2.04 us: 1.03x slower                                          |
| async_tree_cpu_io_mixed   | 522 ms                                                 | 539 ms: 1.03x slower                                           |
| async_tree_io             | 705 ms                                                 | 729 ms: 1.03x slower                                           |
| sympy_str                 | 144 ms                                                 | 150 ms: 1.04x slower                                           |
| sympy_integrate           | 11.3 ms                                                | 11.8 ms: 1.04x slower                                          |
| pickle                    | 7.22 us                                                | 7.51 us: 1.04x slower                                          |
| python_startup            | 11.4 ms                                                | 11.9 ms: 1.04x slower                                          |
| dulwich_log               | 29.9 ms                                                | 31.3 ms: 1.05x slower                                          |
| regex_effbot              | 2.46 ms                                                | 2.58 ms: 1.05x slower                                          |
| crypto_pyaes              | 48.1 ms                                                | 50.6 ms: 1.05x slower                                          |
| dask                      | 224 ms                                                 | 235 ms: 1.05x slower                                           |
| meteor_contest            | 74.9 ms                                                | 79.0 ms: 1.05x slower                                          |
| pickle_dict               | 17.0 us                                                | 18.1 us: 1.06x slower                                          |
| logging_simple            | 3.41 us                                                | 3.61 us: 1.06x slower                                          |
| logging_format            | 3.69 us                                                | 3.91 us: 1.06x slower                                          |
| docutils                  | 1.46 sec                                               | 1.55 sec: 1.07x slower                                         |
| scimark_monte_carlo       | 47.1 ms                                                | 50.5 ms: 1.07x slower                                          |
| tornado_http              | 71.0 ms                                                | 76.3 ms: 1.08x slower                                          |
| pycparser                 | 667 ms                                                 | 719 ms: 1.08x slower                                           |
| bench_mp_pool             | 41.9 ms                                                | 45.3 ms: 1.08x slower                                          |
| spectral_norm             | 69.7 ms                                                | 75.5 ms: 1.08x slower                                          |
| float                     | 55.4 ms                                                | 60.0 ms: 1.08x slower                                          |
| pickle_list               | 2.67 us                                                | 2.89 us: 1.08x slower                                          |
| richards                  | 30.8 ms                                                | 33.6 ms: 1.09x slower                                          |
| sympy_expand              | 234 ms                                                 | 255 ms: 1.09x slower                                           |
| unpickle_pure_python      | 163 us                                                 | 179 us: 1.09x slower                                           |
| scimark_sparse_mat_mult   | 3.01 ms                                                | 3.33 ms: 1.11x slower                                          |
| regex_v8                  | 15.3 ms                                                | 17.0 ms: 1.11x slower                                          |
| json                      | 2.77 ms                                                | 3.09 ms: 1.11x slower                                          |
| pprint_pformat            | 989 ms                                                 | 1.10 sec: 1.11x slower                                         |
| unpickle                  | 8.32 us                                                | 9.35 us: 1.12x slower                                          |
| regex_compile             | 73.9 ms                                                | 83.2 ms: 1.13x slower                                          |
| bench_thread_pool         | 461 us                                                 | 519 us: 1.13x slower                                           |
| go                        | 102 ms                                                 | 115 ms: 1.13x slower                                           |
| pprint_safe_repr          | 479 ms                                                 | 542 ms: 1.13x slower                                           |
| json_loads                | 15.8 us                                                | 17.9 us: 1.13x slower                                          |
| coroutines                | 16.6 ms                                                | 18.8 ms: 1.13x slower                                          |
| python_startup_no_site    | 9.15 ms                                                | 10.4 ms: 1.14x slower                                          |
| scimark_lu                | 67.8 ms                                                | 77.4 ms: 1.14x slower                                          |
| logging_silent            | 64.5 ns                                                | 74.9 ns: 1.16x slower                                          |
| tomli_loads               | 1.30 sec                                               | 1.53 sec: 1.18x slower                                         |
| scimark_fft               | 187 ms                                                 | 220 ms: 1.18x slower                                           |
| chameleon                 | 4.17 ms                                                | 4.92 ms: 1.18x slower                                          |
| coverage                  | 41.4 ms                                                | 48.7 ms: 1.18x slower                                          |
| 2to3                      | 155 ms                                                 | 183 ms: 1.18x slower                                           |
| pyflate                   | 297 ms                                                 | 352 ms: 1.18x slower                                           |
| nqueens                   | 54.6 ms                                                | 65.6 ms: 1.20x slower                                          |
| sqlglot_normalize         | 160 ms                                                 | 193 ms: 1.21x slower                                           |
| sqlglot_optimize          | 29.6 ms                                                | 35.9 ms: 1.21x slower                                          |
| nbody                     | 68.7 ms                                                | 83.5 ms: 1.22x slower                                          |
| unpickle_list             | 2.77 us                                                | 3.37 us: 1.22x slower                                          |
| sqlite_synth              | 1.35 us                                                | 1.64 us: 1.22x slower                                          |
| fannkuch                  | 247 ms                                                 | 311 ms: 1.26x slower                                           |
| hexiom                    | 4.55 ms                                                | 5.89 ms: 1.29x slower                                          |
| xml_etree_iterparse       | 68.2 ms                                                | 88.5 ms: 1.30x slower                                          |
| xml_etree_process         | 34.0 ms                                                | 44.5 ms: 1.31x slower                                          |
| xml_etree_parse           | 107 ms                                                 | 140 ms: 1.31x slower                                           |
| xml_etree_generate        | 46.8 ms                                                | 62.5 ms: 1.33x slower                                          |
| mypy2                     | 191 ms                                                 | 271 ms: 1.42x slower                                           |
| scimark_sor               | 75.2 ms                                                | 108 ms: 1.44x slower                                           |
| telco                     | 3.17 ms                                                | 4.79 ms: 1.51x slower                                          |
| async_generators          | 192 ms                                                 | 321 ms: 1.67x slower                                           |
| Geometric mean            | (ref)                                                  | 1.06x slower                                                   |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg
Ignored benchmarks (11) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.04x
- 95% likely to have a slowdown of 1.04x
- 99% likely to have a slowdown of 1.03x
