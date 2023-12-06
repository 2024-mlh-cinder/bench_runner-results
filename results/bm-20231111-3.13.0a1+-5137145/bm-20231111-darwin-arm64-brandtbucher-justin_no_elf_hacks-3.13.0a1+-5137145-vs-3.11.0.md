
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin_no_elf_hacks
- machine: darwin-arm64
- commit hash: 5137145
- commit date: 2023-11-11
- overall geometric mean: 1.04x slower \*
- HPT reliability: 99.98%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 155 ms                                                 | 180 ms: 1.16x slower                                                        |
| chameleon      | 4.17 ms                                                | 4.75 ms: 1.14x slower                                                       |
| docutils       | 1.46 sec                                               | 1.53 sec: 1.05x slower                                                      |
| Geometric mean | (ref)                                                  | 1.09x slower                                                                |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none            | 282 ms                                                 | 256 ms: 1.10x faster                                                        |
| async_tree_memoization     | 361 ms                                                 | 334 ms: 1.08x faster                                                        |
| async_tree_memoization_tg  | 357 ms                                                 | 336 ms: 1.06x faster                                                        |
| async_tree_io_tg           | 734 ms                                                 | 692 ms: 1.06x faster                                                        |
| async_tree_none_tg         | 280 ms                                                 | 270 ms: 1.04x faster                                                        |
| async_tree_cpu_io_mixed_tg | 554 ms                                                 | 546 ms: 1.01x faster                                                        |
| async_tree_io              | 705 ms                                                 | 710 ms: 1.01x slower                                                        |
| async_tree_cpu_io_mixed    | 522 ms                                                 | 529 ms: 1.01x slower                                                        |
| Geometric mean             | (ref)                                                  | 1.04x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 281 ms                                                 | 283 ms: 1.00x slower                                                        |
| float          | 55.4 ms                                                | 60.3 ms: 1.09x slower                                                       |
| nbody          | 68.7 ms                                                | 83.6 ms: 1.22x slower                                                       |
| Geometric mean | (ref)                                                  | 1.10x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_dna      | 149 ms                                                 | 149 ms: 1.00x faster                                                        |
| regex_effbot   | 2.46 ms                                                | 2.56 ms: 1.04x slower                                                       |
| regex_v8       | 15.3 ms                                                | 17.0 ms: 1.11x slower                                                       |
| regex_compile  | 73.9 ms                                                | 82.0 ms: 1.11x slower                                                       |
| Geometric mean | (ref)                                                  | 1.06x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 7.58 ms                                                | 6.66 ms: 1.14x faster                                                       |
| pickle_pure_python   | 211 us                                                 | 200 us: 1.05x faster                                                        |
| unpickle_pure_python | 163 us                                                 | 164 us: 1.01x slower                                                        |
| xml_etree_parse      | 107 ms                                                 | 110 ms: 1.02x slower                                                        |
| pickle               | 7.22 us                                                | 7.46 us: 1.03x slower                                                       |
| pickle_dict          | 17.0 us                                                | 17.8 us: 1.04x slower                                                       |
| pickle_list          | 2.67 us                                                | 2.88 us: 1.08x slower                                                       |
| unpickle             | 8.32 us                                                | 9.19 us: 1.10x slower                                                       |
| json_loads           | 15.8 us                                                | 17.7 us: 1.12x slower                                                       |
| xml_etree_iterparse  | 68.2 ms                                                | 76.8 ms: 1.13x slower                                                       |
| tomli_loads          | 1.30 sec                                               | 1.49 sec: 1.14x slower                                                      |
| unpickle_list        | 2.77 us                                                | 3.20 us: 1.16x slower                                                       |
| xml_etree_process    | 34.0 ms                                                | 40.0 ms: 1.18x slower                                                       |
| xml_etree_generate   | 46.8 ms                                                | 58.6 ms: 1.25x slower                                                       |
| Geometric mean       | (ref)                                                  | 1.07x slower                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 11.4 ms                                                | 12.6 ms: 1.11x slower                                                       |
| python_startup_no_site | 9.15 ms                                                | 11.2 ms: 1.22x slower                                                       |
| Geometric mean         | (ref)                                                  | 1.16x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 8.22 ms                                                | 8.00 ms: 1.03x faster                                                       |

All benchmarks:
===============

| Benchmark                  | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols   | 323 us                                                 | 76.5 us: 4.22x faster                                                       |
| asyncio_tcp                | 650 ms                                                 | 443 ms: 1.47x faster                                                        |
| unpack_sequence            | 32.3 ns                                                | 26.3 ns: 1.23x faster                                                       |
| generators                 | 29.2 ms                                                | 24.5 ms: 1.19x faster                                                       |
| json_dumps                 | 7.58 ms                                                | 6.66 ms: 1.14x faster                                                       |
| deepcopy_memo              | 28.9 us                                                | 25.8 us: 1.12x faster                                                       |
| asyncio_tcp_ssl            | 1.44 sec                                               | 1.29 sec: 1.11x faster                                                      |
| async_tree_none            | 282 ms                                                 | 256 ms: 1.10x faster                                                        |
| chaos                      | 48.2 ms                                                | 44.1 ms: 1.09x faster                                                       |
| raytrace                   | 200 ms                                                 | 184 ms: 1.09x faster                                                        |
| async_tree_memoization     | 361 ms                                                 | 334 ms: 1.08x faster                                                        |
| sympy_sum                  | 81.6 ms                                                | 76.5 ms: 1.07x faster                                                       |
| async_tree_memoization_tg  | 357 ms                                                 | 336 ms: 1.06x faster                                                        |
| async_tree_io_tg           | 734 ms                                                 | 692 ms: 1.06x faster                                                        |
| sqlglot_parse              | 886 us                                                 | 840 us: 1.05x faster                                                        |
| pickle_pure_python         | 211 us                                                 | 200 us: 1.05x faster                                                        |
| deepcopy                   | 233 us                                                 | 222 us: 1.05x faster                                                        |
| comprehensions             | 14.7 us                                                | 14.0 us: 1.04x faster                                                       |
| async_tree_none_tg         | 280 ms                                                 | 270 ms: 1.04x faster                                                        |
| mako                       | 8.22 ms                                                | 8.00 ms: 1.03x faster                                                       |
| sqlglot_transpile          | 1.05 ms                                                | 1.02 ms: 1.03x faster                                                       |
| mdp                        | 1.73 sec                                               | 1.70 sec: 1.02x faster                                                      |
| create_gc_cycles           | 715 us                                                 | 702 us: 1.02x faster                                                        |
| deltablue                  | 2.70 ms                                                | 2.66 ms: 1.01x faster                                                       |
| async_tree_cpu_io_mixed_tg | 554 ms                                                 | 546 ms: 1.01x faster                                                        |
| deepcopy_reduce            | 1.98 us                                                | 1.97 us: 1.00x faster                                                       |
| regex_dna                  | 149 ms                                                 | 149 ms: 1.00x faster                                                        |
| asyncio_websockets         | 544 ms                                                 | 545 ms: 1.00x slower                                                        |
| pidigits                   | 281 ms                                                 | 283 ms: 1.00x slower                                                        |
| richards_super             | 36.8 ms                                                | 37.0 ms: 1.00x slower                                                       |
| async_tree_io              | 705 ms                                                 | 710 ms: 1.01x slower                                                        |
| gc_traversal               | 2.39 ms                                                | 2.40 ms: 1.01x slower                                                       |
| unpickle_pure_python       | 163 us                                                 | 164 us: 1.01x slower                                                        |
| sympy_str                  | 144 ms                                                 | 146 ms: 1.01x slower                                                        |
| async_tree_cpu_io_mixed    | 522 ms                                                 | 529 ms: 1.01x slower                                                        |
| sympy_integrate            | 11.3 ms                                                | 11.5 ms: 1.02x slower                                                       |
| xml_etree_parse            | 107 ms                                                 | 110 ms: 1.02x slower                                                        |
| dulwich_log                | 29.9 ms                                                | 30.8 ms: 1.03x slower                                                       |
| pickle                     | 7.22 us                                                | 7.46 us: 1.03x slower                                                       |
| pathlib                    | 28.5 ms                                                | 29.5 ms: 1.04x slower                                                       |
| meteor_contest             | 74.9 ms                                                | 77.7 ms: 1.04x slower                                                       |
| crypto_pyaes               | 48.1 ms                                                | 50.1 ms: 1.04x slower                                                       |
| regex_effbot               | 2.46 ms                                                | 2.56 ms: 1.04x slower                                                       |
| pickle_dict                | 17.0 us                                                | 17.8 us: 1.04x slower                                                       |
| spectral_norm              | 69.7 ms                                                | 72.9 ms: 1.05x slower                                                       |
| docutils                   | 1.46 sec                                               | 1.53 sec: 1.05x slower                                                      |
| logging_format             | 3.69 us                                                | 3.87 us: 1.05x slower                                                       |
| logging_simple             | 3.41 us                                                | 3.58 us: 1.05x slower                                                       |
| scimark_monte_carlo        | 47.1 ms                                                | 49.5 ms: 1.05x slower                                                       |
| pycparser                  | 667 ms                                                 | 705 ms: 1.06x slower                                                        |
| go                         | 102 ms                                                 | 109 ms: 1.06x slower                                                        |
| sympy_expand               | 234 ms                                                 | 250 ms: 1.07x slower                                                        |
| pickle_list                | 2.67 us                                                | 2.88 us: 1.08x slower                                                       |
| json                       | 2.77 ms                                                | 3.00 ms: 1.08x slower                                                       |
| coroutines                 | 16.6 ms                                                | 17.9 ms: 1.08x slower                                                       |
| pprint_pformat             | 989 ms                                                 | 1.08 sec: 1.09x slower                                                      |
| float                      | 55.4 ms                                                | 60.3 ms: 1.09x slower                                                       |
| bench_mp_pool              | 41.9 ms                                                | 45.8 ms: 1.09x slower                                                       |
| richards                   | 30.8 ms                                                | 33.6 ms: 1.09x slower                                                       |
| logging_silent             | 64.5 ns                                                | 70.9 ns: 1.10x slower                                                       |
| bench_thread_pool          | 461 us                                                 | 507 us: 1.10x slower                                                        |
| pprint_safe_repr           | 479 ms                                                 | 528 ms: 1.10x slower                                                        |
| unpickle                   | 8.32 us                                                | 9.19 us: 1.10x slower                                                       |
| python_startup             | 11.4 ms                                                | 12.6 ms: 1.11x slower                                                       |
| regex_v8                   | 15.3 ms                                                | 17.0 ms: 1.11x slower                                                       |
| regex_compile              | 73.9 ms                                                | 82.0 ms: 1.11x slower                                                       |
| scimark_lu                 | 67.8 ms                                                | 75.8 ms: 1.12x slower                                                       |
| json_loads                 | 15.8 us                                                | 17.7 us: 1.12x slower                                                       |
| xml_etree_iterparse        | 68.2 ms                                                | 76.8 ms: 1.13x slower                                                       |
| chameleon                  | 4.17 ms                                                | 4.75 ms: 1.14x slower                                                       |
| tomli_loads                | 1.30 sec                                               | 1.49 sec: 1.14x slower                                                      |
| scimark_sparse_mat_mult    | 3.01 ms                                                | 3.46 ms: 1.15x slower                                                       |
| unpickle_list              | 2.77 us                                                | 3.20 us: 1.16x slower                                                       |
| 2to3                       | 155 ms                                                 | 180 ms: 1.16x slower                                                        |
| pyflate                    | 297 ms                                                 | 345 ms: 1.16x slower                                                        |
| scimark_fft                | 187 ms                                                 | 220 ms: 1.18x slower                                                        |
| coverage                   | 41.4 ms                                                | 48.6 ms: 1.18x slower                                                       |
| xml_etree_process          | 34.0 ms                                                | 40.0 ms: 1.18x slower                                                       |
| sqlglot_normalize          | 160 ms                                                 | 188 ms: 1.18x slower                                                        |
| sqlglot_optimize           | 29.6 ms                                                | 35.1 ms: 1.19x slower                                                       |
| nqueens                    | 54.6 ms                                                | 65.2 ms: 1.20x slower                                                       |
| fannkuch                   | 247 ms                                                 | 299 ms: 1.21x slower                                                        |
| nbody                      | 68.7 ms                                                | 83.6 ms: 1.22x slower                                                       |
| hexiom                     | 4.55 ms                                                | 5.55 ms: 1.22x slower                                                       |
| sqlite_synth               | 1.35 us                                                | 1.64 us: 1.22x slower                                                       |
| python_startup_no_site     | 9.15 ms                                                | 11.2 ms: 1.22x slower                                                       |
| xml_etree_generate         | 46.8 ms                                                | 58.6 ms: 1.25x slower                                                       |
| mypy2                      | 191 ms                                                 | 269 ms: 1.41x slower                                                        |
| scimark_sor                | 75.2 ms                                                | 107 ms: 1.42x slower                                                        |
| telco                      | 3.17 ms                                                | 4.75 ms: 1.50x slower                                                       |
| async_generators           | 192 ms                                                 | 316 ms: 1.64x slower                                                        |
| Geometric mean             | (ref)                                                  | 1.04x slower                                                                |

Benchmark hidden because not significant (1): tornado_http
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.98% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
