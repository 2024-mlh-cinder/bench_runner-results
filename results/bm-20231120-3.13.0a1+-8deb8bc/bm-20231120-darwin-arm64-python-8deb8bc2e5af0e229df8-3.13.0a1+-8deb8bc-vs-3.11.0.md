
# Results vs. 3.11.0

- fork: python
- ref: 8deb8bc2e5af0e229df8
- machine: darwin-arm64
- commit hash: 8deb8bc
- commit date: 2023-11-20
- overall geometric mean: 1.02x slower \*
- HPT reliability: 99.47%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 155 ms                                                 | 174 ms: 1.12x slower                                                   |
| chameleon      | 4.17 ms                                                | 4.83 ms: 1.16x slower                                                  |
| docutils       | 1.46 sec                                               | 1.49 sec: 1.03x slower                                                 |
| Geometric mean | (ref)                                                  | 1.07x slower                                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none            | 282 ms                                                 | 255 ms: 1.10x faster                                                   |
| async_tree_memoization     | 361 ms                                                 | 331 ms: 1.09x faster                                                   |
| async_tree_io_tg           | 734 ms                                                 | 686 ms: 1.07x faster                                                   |
| async_tree_memoization_tg  | 357 ms                                                 | 334 ms: 1.07x faster                                                   |
| async_tree_none_tg         | 280 ms                                                 | 268 ms: 1.05x faster                                                   |
| async_tree_cpu_io_mixed_tg | 554 ms                                                 | 544 ms: 1.02x faster                                                   |
| async_tree_cpu_io_mixed    | 522 ms                                                 | 527 ms: 1.01x slower                                                   |
| Geometric mean             | (ref)                                                  | 1.05x faster                                                           |

Benchmark hidden because not significant (1): async_tree_io

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| float          | 55.4 ms                                                | 58.4 ms: 1.05x slower                                                  |
| nbody          | 68.7 ms                                                | 79.0 ms: 1.15x slower                                                  |
| Geometric mean | (ref)                                                  | 1.07x slower                                                           |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_dna      | 149 ms                                                 | 149 ms: 1.00x faster                                                   |
| regex_effbot   | 2.46 ms                                                | 2.57 ms: 1.04x slower                                                  |
| regex_compile  | 73.9 ms                                                | 78.7 ms: 1.06x slower                                                  |
| regex_v8       | 15.3 ms                                                | 16.9 ms: 1.10x slower                                                  |
| Geometric mean | (ref)                                                  | 1.05x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| json_dumps           | 7.58 ms                                                | 6.56 ms: 1.15x faster                                                  |
| pickle_pure_python   | 211 us                                                 | 203 us: 1.04x faster                                                   |
| unpickle_pure_python | 163 us                                                 | 161 us: 1.02x faster                                                   |
| pickle               | 7.22 us                                                | 7.35 us: 1.02x slower                                                  |
| pickle_dict          | 17.0 us                                                | 18.0 us: 1.06x slower                                                  |
| pickle_list          | 2.67 us                                                | 2.90 us: 1.09x slower                                                  |
| unpickle             | 8.32 us                                                | 9.19 us: 1.10x slower                                                  |
| json_loads           | 15.8 us                                                | 17.4 us: 1.10x slower                                                  |
| xml_etree_iterparse  | 68.2 ms                                                | 76.2 ms: 1.12x slower                                                  |
| unpickle_list        | 2.77 us                                                | 3.15 us: 1.14x slower                                                  |
| xml_etree_process    | 34.0 ms                                                | 40.2 ms: 1.18x slower                                                  |
| tomli_loads          | 1.30 sec                                               | 1.58 sec: 1.21x slower                                                 |
| xml_etree_generate   | 46.8 ms                                                | 58.4 ms: 1.25x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.07x slower                                                           |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 11.4 ms                                                | 11.6 ms: 1.03x slower                                                  |
| python_startup_no_site | 9.15 ms                                                | 10.3 ms: 1.12x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.07x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 8.22 ms                                                | 7.78 ms: 1.06x faster                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols   | 323 us                                                 | 76.4 us: 4.22x faster                                                  |
| asyncio_tcp                | 650 ms                                                 | 407 ms: 1.60x faster                                                   |
| asyncio_websockets         | 544 ms                                                 | 408 ms: 1.33x faster                                                   |
| pathlib                    | 28.5 ms                                                | 23.6 ms: 1.21x faster                                                  |
| comprehensions             | 14.7 us                                                | 12.6 us: 1.17x faster                                                  |
| json_dumps                 | 7.58 ms                                                | 6.56 ms: 1.15x faster                                                  |
| unpack_sequence            | 32.3 ns                                                | 28.0 ns: 1.15x faster                                                  |
| deepcopy_memo              | 28.9 us                                                | 25.2 us: 1.15x faster                                                  |
| generators                 | 29.2 ms                                                | 25.6 ms: 1.14x faster                                                  |
| asyncio_tcp_ssl            | 1.44 sec                                               | 1.30 sec: 1.11x faster                                                 |
| chaos                      | 48.2 ms                                                | 43.7 ms: 1.10x faster                                                  |
| async_tree_none            | 282 ms                                                 | 255 ms: 1.10x faster                                                   |
| async_tree_memoization     | 361 ms                                                 | 331 ms: 1.09x faster                                                   |
| deltablue                  | 2.70 ms                                                | 2.48 ms: 1.09x faster                                                  |
| sympy_sum                  | 81.6 ms                                                | 75.6 ms: 1.08x faster                                                  |
| async_tree_io_tg           | 734 ms                                                 | 686 ms: 1.07x faster                                                   |
| async_tree_memoization_tg  | 357 ms                                                 | 334 ms: 1.07x faster                                                   |
| raytrace                   | 200 ms                                                 | 189 ms: 1.06x faster                                                   |
| mdp                        | 1.73 sec                                               | 1.64 sec: 1.06x faster                                                 |
| mako                       | 8.22 ms                                                | 7.78 ms: 1.06x faster                                                  |
| async_tree_none_tg         | 280 ms                                                 | 268 ms: 1.05x faster                                                   |
| sqlglot_parse              | 886 us                                                 | 852 us: 1.04x faster                                                   |
| pickle_pure_python         | 211 us                                                 | 203 us: 1.04x faster                                                   |
| create_gc_cycles           | 715 us                                                 | 701 us: 1.02x faster                                                   |
| async_tree_cpu_io_mixed_tg | 554 ms                                                 | 544 ms: 1.02x faster                                                   |
| sympy_integrate            | 11.3 ms                                                | 11.1 ms: 1.02x faster                                                  |
| unpickle_pure_python       | 163 us                                                 | 161 us: 1.02x faster                                                   |
| sqlglot_transpile          | 1.05 ms                                                | 1.04 ms: 1.01x faster                                                  |
| deepcopy                   | 233 us                                                 | 230 us: 1.01x faster                                                   |
| regex_dna                  | 149 ms                                                 | 149 ms: 1.00x faster                                                   |
| dulwich_log                | 29.9 ms                                                | 30.0 ms: 1.00x slower                                                  |
| async_tree_cpu_io_mixed    | 522 ms                                                 | 527 ms: 1.01x slower                                                   |
| dask                       | 224 ms                                                 | 226 ms: 1.01x slower                                                   |
| pickle                     | 7.22 us                                                | 7.35 us: 1.02x slower                                                  |
| sympy_str                  | 144 ms                                                 | 147 ms: 1.02x slower                                                   |
| python_startup             | 11.4 ms                                                | 11.6 ms: 1.03x slower                                                  |
| docutils                   | 1.46 sec                                               | 1.49 sec: 1.03x slower                                                 |
| scimark_monte_carlo        | 47.1 ms                                                | 48.4 ms: 1.03x slower                                                  |
| crypto_pyaes               | 48.1 ms                                                | 49.7 ms: 1.03x slower                                                  |
| deepcopy_reduce            | 1.98 us                                                | 2.05 us: 1.04x slower                                                  |
| bench_mp_pool              | 41.9 ms                                                | 43.6 ms: 1.04x slower                                                  |
| richards_super             | 36.8 ms                                                | 38.4 ms: 1.04x slower                                                  |
| regex_effbot               | 2.46 ms                                                | 2.57 ms: 1.04x slower                                                  |
| go                         | 102 ms                                                 | 107 ms: 1.04x slower                                                   |
| scimark_sparse_mat_mult    | 3.01 ms                                                | 3.16 ms: 1.05x slower                                                  |
| float                      | 55.4 ms                                                | 58.4 ms: 1.05x slower                                                  |
| pickle_dict                | 17.0 us                                                | 18.0 us: 1.06x slower                                                  |
| regex_compile              | 73.9 ms                                                | 78.7 ms: 1.06x slower                                                  |
| pycparser                  | 667 ms                                                 | 710 ms: 1.06x slower                                                   |
| logging_simple             | 3.41 us                                                | 3.63 us: 1.07x slower                                                  |
| logging_format             | 3.69 us                                                | 3.94 us: 1.07x slower                                                  |
| pprint_pformat             | 989 ms                                                 | 1.06 sec: 1.07x slower                                                 |
| spectral_norm              | 69.7 ms                                                | 75.0 ms: 1.07x slower                                                  |
| hexiom                     | 4.55 ms                                                | 4.96 ms: 1.09x slower                                                  |
| pickle_list                | 2.67 us                                                | 2.90 us: 1.09x slower                                                  |
| json                       | 2.77 ms                                                | 3.03 ms: 1.09x slower                                                  |
| sympy_expand               | 234 ms                                                 | 255 ms: 1.09x slower                                                   |
| pprint_safe_repr           | 479 ms                                                 | 524 ms: 1.09x slower                                                   |
| regex_v8                   | 15.3 ms                                                | 16.9 ms: 1.10x slower                                                  |
| unpickle                   | 8.32 us                                                | 9.19 us: 1.10x slower                                                  |
| json_loads                 | 15.8 us                                                | 17.4 us: 1.10x slower                                                  |
| nqueens                    | 54.6 ms                                                | 60.6 ms: 1.11x slower                                                  |
| scimark_fft                | 187 ms                                                 | 208 ms: 1.11x slower                                                   |
| bench_thread_pool          | 461 us                                                 | 514 us: 1.11x slower                                                   |
| xml_etree_iterparse        | 68.2 ms                                                | 76.2 ms: 1.12x slower                                                  |
| scimark_lu                 | 67.8 ms                                                | 75.9 ms: 1.12x slower                                                  |
| 2to3                       | 155 ms                                                 | 174 ms: 1.12x slower                                                   |
| richards                   | 30.8 ms                                                | 34.5 ms: 1.12x slower                                                  |
| python_startup_no_site     | 9.15 ms                                                | 10.3 ms: 1.12x slower                                                  |
| coroutines                 | 16.6 ms                                                | 18.8 ms: 1.14x slower                                                  |
| logging_silent             | 64.5 ns                                                | 73.3 ns: 1.14x slower                                                  |
| unpickle_list              | 2.77 us                                                | 3.15 us: 1.14x slower                                                  |
| nbody                      | 68.7 ms                                                | 79.0 ms: 1.15x slower                                                  |
| chameleon                  | 4.17 ms                                                | 4.83 ms: 1.16x slower                                                  |
| fannkuch                   | 247 ms                                                 | 287 ms: 1.16x slower                                                   |
| pyflate                    | 297 ms                                                 | 346 ms: 1.16x slower                                                   |
| coverage                   | 41.4 ms                                                | 48.4 ms: 1.17x slower                                                  |
| xml_etree_process          | 34.0 ms                                                | 40.2 ms: 1.18x slower                                                  |
| sqlglot_normalize          | 160 ms                                                 | 191 ms: 1.19x slower                                                   |
| sqlglot_optimize           | 29.6 ms                                                | 35.4 ms: 1.20x slower                                                  |
| tomli_loads                | 1.30 sec                                               | 1.58 sec: 1.21x slower                                                 |
| sqlite_synth               | 1.35 us                                                | 1.65 us: 1.23x slower                                                  |
| xml_etree_generate         | 46.8 ms                                                | 58.4 ms: 1.25x slower                                                  |
| mypy2                      | 191 ms                                                 | 259 ms: 1.36x slower                                                   |
| scimark_sor                | 75.2 ms                                                | 107 ms: 1.42x slower                                                   |
| telco                      | 3.17 ms                                                | 4.64 ms: 1.47x slower                                                  |
| async_generators           | 192 ms                                                 | 304 ms: 1.58x slower                                                   |
| Geometric mean             | (ref)                                                  | 1.02x slower                                                           |

Benchmark hidden because not significant (6): xml_etree_parse, async_tree_io, tornado_http, meteor_contest, gc_traversal, pidigits
Ignored benchmarks (11) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.47% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
