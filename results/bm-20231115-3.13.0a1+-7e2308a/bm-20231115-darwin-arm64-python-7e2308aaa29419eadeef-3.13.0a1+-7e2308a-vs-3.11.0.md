
# Results vs. 3.11.0

- fork: python
- ref: 7e2308aaa29419eadeef
- machine: darwin-arm64
- commit hash: 7e2308a
- commit date: 2023-11-15
- overall geometric mean: 1.04x slower \*
- HPT reliability: 99.99%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-darwin-arm64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 155 ms                                                 | 178 ms: 1.15x slower                                                   |
| chameleon      | 4.17 ms                                                | 4.85 ms: 1.16x slower                                                  |
| docutils       | 1.46 sec                                               | 1.52 sec: 1.04x slower                                                 |
| Geometric mean | (ref)                                                  | 1.09x slower                                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-darwin-arm64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|---------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none           | 282 ms                                                 | 261 ms: 1.08x faster                                                   |
| async_tree_memoization    | 361 ms                                                 | 338 ms: 1.07x faster                                                   |
| async_tree_memoization_tg | 357 ms                                                 | 341 ms: 1.05x faster                                                   |
| async_tree_io_tg          | 734 ms                                                 | 714 ms: 1.03x faster                                                   |
| async_tree_none_tg        | 280 ms                                                 | 275 ms: 1.02x faster                                                   |
| async_tree_cpu_io_mixed   | 522 ms                                                 | 534 ms: 1.02x slower                                                   |
| async_tree_io             | 705 ms                                                 | 727 ms: 1.03x slower                                                   |
| Geometric mean            | (ref)                                                  | 1.02x faster                                                           |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-darwin-arm64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 281 ms                                                 | 283 ms: 1.00x slower                                                   |
| float          | 55.4 ms                                                | 59.9 ms: 1.08x slower                                                  |
| nbody          | 68.7 ms                                                | 79.6 ms: 1.16x slower                                                  |
| Geometric mean | (ref)                                                  | 1.08x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-darwin-arm64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_effbot   | 2.46 ms                                                | 2.56 ms: 1.04x slower                                                  |
| regex_compile  | 73.9 ms                                                | 78.7 ms: 1.06x slower                                                  |
| regex_v8       | 15.3 ms                                                | 17.0 ms: 1.11x slower                                                  |
| Geometric mean | (ref)                                                  | 1.05x slower                                                           |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-darwin-arm64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| json_dumps           | 7.58 ms                                                | 6.60 ms: 1.15x faster                                                  |
| pickle_pure_python   | 211 us                                                 | 202 us: 1.04x faster                                                   |
| unpickle_pure_python | 163 us                                                 | 162 us: 1.01x faster                                                   |
| pickle               | 7.22 us                                                | 7.44 us: 1.03x slower                                                  |
| pickle_dict          | 17.0 us                                                | 18.0 us: 1.06x slower                                                  |
| unpickle             | 8.32 us                                                | 9.09 us: 1.09x slower                                                  |
| pickle_list          | 2.67 us                                                | 2.96 us: 1.11x slower                                                  |
| json_loads           | 15.8 us                                                | 17.8 us: 1.13x slower                                                  |
| unpickle_list        | 2.77 us                                                | 3.12 us: 1.13x slower                                                  |
| xml_etree_iterparse  | 68.2 ms                                                | 77.6 ms: 1.14x slower                                                  |
| xml_etree_process    | 34.0 ms                                                | 41.0 ms: 1.21x slower                                                  |
| tomli_loads          | 1.30 sec                                               | 1.60 sec: 1.22x slower                                                 |
| xml_etree_generate   | 46.8 ms                                                | 59.3 ms: 1.27x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.08x slower                                                           |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-darwin-arm64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 11.4 ms                                                | 12.0 ms: 1.05x slower                                                  |
| python_startup_no_site | 9.15 ms                                                | 10.6 ms: 1.16x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.10x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-darwin-arm64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 8.22 ms                                                | 7.81 ms: 1.05x faster                                                  |

All benchmarks:
===============

| Benchmark                 | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-darwin-arm64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|---------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols  | 323 us                                                 | 77.9 us: 4.14x faster                                                  |
| asyncio_tcp               | 650 ms                                                 | 422 ms: 1.54x faster                                                   |
| comprehensions            | 14.7 us                                                | 12.6 us: 1.16x faster                                                  |
| json_dumps                | 7.58 ms                                                | 6.60 ms: 1.15x faster                                                  |
| deepcopy_memo             | 28.9 us                                                | 25.2 us: 1.15x faster                                                  |
| unpack_sequence           | 32.3 ns                                                | 28.3 ns: 1.14x faster                                                  |
| generators                | 29.2 ms                                                | 25.7 ms: 1.14x faster                                                  |
| asyncio_tcp_ssl           | 1.44 sec                                               | 1.31 sec: 1.10x faster                                                 |
| chaos                     | 48.2 ms                                                | 44.3 ms: 1.09x faster                                                  |
| deltablue                 | 2.70 ms                                                | 2.49 ms: 1.08x faster                                                  |
| async_tree_none           | 282 ms                                                 | 261 ms: 1.08x faster                                                   |
| sympy_sum                 | 81.6 ms                                                | 76.0 ms: 1.07x faster                                                  |
| async_tree_memoization    | 361 ms                                                 | 338 ms: 1.07x faster                                                   |
| mako                      | 8.22 ms                                                | 7.81 ms: 1.05x faster                                                  |
| async_tree_memoization_tg | 357 ms                                                 | 341 ms: 1.05x faster                                                   |
| raytrace                  | 200 ms                                                 | 192 ms: 1.04x faster                                                   |
| pickle_pure_python        | 211 us                                                 | 202 us: 1.04x faster                                                   |
| sqlglot_parse             | 886 us                                                 | 853 us: 1.04x faster                                                   |
| mdp                       | 1.73 sec                                               | 1.68 sec: 1.04x faster                                                 |
| async_tree_io_tg          | 734 ms                                                 | 714 ms: 1.03x faster                                                   |
| async_tree_none_tg        | 280 ms                                                 | 275 ms: 1.02x faster                                                   |
| deepcopy                  | 233 us                                                 | 229 us: 1.02x faster                                                   |
| unpickle_pure_python      | 163 us                                                 | 162 us: 1.01x faster                                                   |
| sqlglot_transpile         | 1.05 ms                                                | 1.04 ms: 1.01x faster                                                  |
| meteor_contest            | 74.9 ms                                                | 75.1 ms: 1.00x slower                                                  |
| pidigits                  | 281 ms                                                 | 283 ms: 1.00x slower                                                   |
| asyncio_websockets        | 544 ms                                                 | 547 ms: 1.01x slower                                                   |
| sympy_str                 | 144 ms                                                 | 147 ms: 1.02x slower                                                   |
| create_gc_cycles          | 715 us                                                 | 729 us: 1.02x slower                                                   |
| crypto_pyaes              | 48.1 ms                                                | 49.3 ms: 1.02x slower                                                  |
| gc_traversal              | 2.39 ms                                                | 2.44 ms: 1.02x slower                                                  |
| async_tree_cpu_io_mixed   | 522 ms                                                 | 534 ms: 1.02x slower                                                   |
| async_tree_io             | 705 ms                                                 | 727 ms: 1.03x slower                                                   |
| pickle                    | 7.22 us                                                | 7.44 us: 1.03x slower                                                  |
| deepcopy_reduce           | 1.98 us                                                | 2.05 us: 1.03x slower                                                  |
| dulwich_log               | 29.9 ms                                                | 30.9 ms: 1.04x slower                                                  |
| scimark_monte_carlo       | 47.1 ms                                                | 48.8 ms: 1.04x slower                                                  |
| dask                      | 224 ms                                                 | 233 ms: 1.04x slower                                                   |
| regex_effbot              | 2.46 ms                                                | 2.56 ms: 1.04x slower                                                  |
| richards_super            | 36.8 ms                                                | 38.5 ms: 1.04x slower                                                  |
| docutils                  | 1.46 sec                                               | 1.52 sec: 1.04x slower                                                 |
| go                        | 102 ms                                                 | 107 ms: 1.05x slower                                                   |
| python_startup            | 11.4 ms                                                | 12.0 ms: 1.05x slower                                                  |
| pickle_dict               | 17.0 us                                                | 18.0 us: 1.06x slower                                                  |
| scimark_sparse_mat_mult   | 3.01 ms                                                | 3.18 ms: 1.06x slower                                                  |
| regex_compile             | 73.9 ms                                                | 78.7 ms: 1.06x slower                                                  |
| bench_mp_pool             | 41.9 ms                                                | 44.7 ms: 1.07x slower                                                  |
| logging_format            | 3.69 us                                                | 3.95 us: 1.07x slower                                                  |
| pycparser                 | 667 ms                                                 | 717 ms: 1.08x slower                                                   |
| pprint_pformat            | 989 ms                                                 | 1.06 sec: 1.08x slower                                                 |
| spectral_norm             | 69.7 ms                                                | 75.1 ms: 1.08x slower                                                  |
| logging_simple            | 3.41 us                                                | 3.68 us: 1.08x slower                                                  |
| float                     | 55.4 ms                                                | 59.9 ms: 1.08x slower                                                  |
| unpickle                  | 8.32 us                                                | 9.09 us: 1.09x slower                                                  |
| hexiom                    | 4.55 ms                                                | 4.99 ms: 1.10x slower                                                  |
| json                      | 2.77 ms                                                | 3.05 ms: 1.10x slower                                                  |
| sympy_expand              | 234 ms                                                 | 257 ms: 1.10x slower                                                   |
| pprint_safe_repr          | 479 ms                                                 | 527 ms: 1.10x slower                                                   |
| nqueens                   | 54.6 ms                                                | 60.1 ms: 1.10x slower                                                  |
| regex_v8                  | 15.3 ms                                                | 17.0 ms: 1.11x slower                                                  |
| pickle_list               | 2.67 us                                                | 2.96 us: 1.11x slower                                                  |
| scimark_lu                | 67.8 ms                                                | 75.3 ms: 1.11x slower                                                  |
| scimark_fft               | 187 ms                                                 | 210 ms: 1.12x slower                                                   |
| json_loads                | 15.8 us                                                | 17.8 us: 1.13x slower                                                  |
| unpickle_list             | 2.77 us                                                | 3.12 us: 1.13x slower                                                  |
| bench_thread_pool         | 461 us                                                 | 520 us: 1.13x slower                                                   |
| xml_etree_iterparse       | 68.2 ms                                                | 77.6 ms: 1.14x slower                                                  |
| richards                  | 30.8 ms                                                | 35.1 ms: 1.14x slower                                                  |
| 2to3                      | 155 ms                                                 | 178 ms: 1.15x slower                                                   |
| coroutines                | 16.6 ms                                                | 19.1 ms: 1.15x slower                                                  |
| python_startup_no_site    | 9.15 ms                                                | 10.6 ms: 1.16x slower                                                  |
| nbody                     | 68.7 ms                                                | 79.6 ms: 1.16x slower                                                  |
| chameleon                 | 4.17 ms                                                | 4.85 ms: 1.16x slower                                                  |
| coverage                  | 41.4 ms                                                | 48.1 ms: 1.16x slower                                                  |
| logging_silent            | 64.5 ns                                                | 75.0 ns: 1.16x slower                                                  |
| pyflate                   | 297 ms                                                 | 350 ms: 1.18x slower                                                   |
| fannkuch                  | 247 ms                                                 | 294 ms: 1.19x slower                                                   |
| sqlglot_normalize         | 160 ms                                                 | 193 ms: 1.21x slower                                                   |
| xml_etree_process         | 34.0 ms                                                | 41.0 ms: 1.21x slower                                                  |
| sqlglot_optimize          | 29.6 ms                                                | 35.7 ms: 1.21x slower                                                  |
| sqlite_synth              | 1.35 us                                                | 1.63 us: 1.21x slower                                                  |
| tomli_loads               | 1.30 sec                                               | 1.60 sec: 1.22x slower                                                 |
| xml_etree_generate        | 46.8 ms                                                | 59.3 ms: 1.27x slower                                                  |
| mypy2                     | 191 ms                                                 | 265 ms: 1.39x slower                                                   |
| scimark_sor               | 75.2 ms                                                | 108 ms: 1.43x slower                                                   |
| telco                     | 3.17 ms                                                | 4.63 ms: 1.46x slower                                                  |
| async_generators          | 192 ms                                                 | 308 ms: 1.60x slower                                                   |
| Geometric mean            | (ref)                                                  | 1.04x slower                                                           |

Benchmark hidden because not significant (6): async_tree_cpu_io_mixed_tg, tornado_http, regex_dna, sympy_integrate, pathlib, xml_etree_parse
Ignored benchmarks (11) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.99% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
