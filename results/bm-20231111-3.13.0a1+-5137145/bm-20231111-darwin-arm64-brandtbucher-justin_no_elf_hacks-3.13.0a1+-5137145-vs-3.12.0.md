
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_no_elf_hacks
- machine: darwin-arm64
- commit hash: 5137145
- commit date: 2023-11-11
- overall geometric mean: 1.03x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 171 ms                                                 | 180 ms: 1.06x slower                                                        |
| chameleon      | 4.51 ms                                                | 4.75 ms: 1.05x slower                                                       |
| docutils       | 1.54 sec                                               | 1.53 sec: 1.01x faster                                                      |
| Geometric mean | (ref)                                                  | 1.03x slower                                                                |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none            | 262 ms                                                 | 256 ms: 1.02x faster                                                        |
| async_tree_cpu_io_mixed_tg | 535 ms                                                 | 546 ms: 1.02x slower                                                        |
| async_tree_io_tg           | 673 ms                                                 | 692 ms: 1.03x slower                                                        |
| async_tree_memoization_tg  | 320 ms                                                 | 336 ms: 1.05x slower                                                        |
| async_tree_io              | 669 ms                                                 | 710 ms: 1.06x slower                                                        |
| async_tree_none_tg         | 254 ms                                                 | 270 ms: 1.06x slower                                                        |
| async_tree_memoization     | 309 ms                                                 | 334 ms: 1.08x slower                                                        |
| Geometric mean             | (ref)                                                  | 1.04x slower                                                                |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 282 ms                                                 | 283 ms: 1.00x slower                                                        |
| float          | 58.1 ms                                                | 60.3 ms: 1.04x slower                                                       |
| nbody          | 68.5 ms                                                | 83.6 ms: 1.22x slower                                                       |
| Geometric mean | (ref)                                                  | 1.08x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_dna      | 153 ms                                                 | 149 ms: 1.03x faster                                                        |
| regex_effbot   | 2.59 ms                                                | 2.56 ms: 1.01x faster                                                       |
| regex_v8       | 15.7 ms                                                | 17.0 ms: 1.08x slower                                                       |
| regex_compile  | 75.6 ms                                                | 82.0 ms: 1.09x slower                                                       |
| Geometric mean | (ref)                                                  | 1.03x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_dict          | 18.0 us                                                | 17.8 us: 1.01x faster                                                       |
| unpickle_list        | 3.24 us                                                | 3.20 us: 1.01x faster                                                       |
| unpickle             | 9.25 us                                                | 9.19 us: 1.01x faster                                                       |
| pickle               | 7.42 us                                                | 7.46 us: 1.01x slower                                                       |
| json_dumps           | 6.46 ms                                                | 6.66 ms: 1.03x slower                                                       |
| xml_etree_iterparse  | 74.6 ms                                                | 76.8 ms: 1.03x slower                                                       |
| xml_etree_process    | 38.7 ms                                                | 40.0 ms: 1.03x slower                                                       |
| xml_etree_generate   | 55.9 ms                                                | 58.6 ms: 1.05x slower                                                       |
| pickle_pure_python   | 188 us                                                 | 200 us: 1.06x slower                                                        |
| tomli_loads          | 1.39 sec                                               | 1.49 sec: 1.07x slower                                                      |
| unpickle_pure_python | 145 us                                                 | 164 us: 1.14x slower                                                        |
| Geometric mean       | (ref)                                                  | 1.03x slower                                                                |

Benchmark hidden because not significant (3): pickle_list, json_loads, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 11.9 ms                                                | 12.6 ms: 1.05x slower                                                       |
| python_startup_no_site | 9.71 ms                                                | 11.2 ms: 1.15x slower                                                       |
| Geometric mean         | (ref)                                                  | 1.10x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.53 ms                                                | 8.00 ms: 1.06x slower                                                       |

All benchmarks:
===============

| Benchmark                  | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| raytrace                   | 246 ms                                                 | 184 ms: 1.33x faster                                                        |
| typing_runtime_protocols   | 90.8 us                                                | 76.5 us: 1.19x faster                                                       |
| generators                 | 28.3 ms                                                | 24.5 ms: 1.16x faster                                                       |
| comprehensions             | 15.8 us                                                | 14.0 us: 1.12x faster                                                       |
| unpack_sequence            | 28.4 ns                                                | 26.3 ns: 1.08x faster                                                       |
| sqlglot_parse              | 897 us                                                 | 840 us: 1.07x faster                                                        |
| sqlglot_transpile          | 1.08 ms                                                | 1.02 ms: 1.05x faster                                                       |
| crypto_pyaes               | 52.0 ms                                                | 50.1 ms: 1.04x faster                                                       |
| sympy_sum                  | 79.5 ms                                                | 76.5 ms: 1.04x faster                                                       |
| deepcopy_reduce            | 2.05 us                                                | 1.97 us: 1.04x faster                                                       |
| sympy_str                  | 151 ms                                                 | 146 ms: 1.04x faster                                                        |
| logging_format             | 3.99 us                                                | 3.87 us: 1.03x faster                                                       |
| logging_simple             | 3.69 us                                                | 3.58 us: 1.03x faster                                                       |
| regex_dna                  | 153 ms                                                 | 149 ms: 1.03x faster                                                        |
| spectral_norm              | 74.6 ms                                                | 72.9 ms: 1.02x faster                                                       |
| async_tree_none            | 262 ms                                                 | 256 ms: 1.02x faster                                                        |
| chaos                      | 44.8 ms                                                | 44.1 ms: 1.02x faster                                                       |
| deepcopy                   | 225 us                                                 | 222 us: 1.01x faster                                                        |
| pickle_dict                | 18.0 us                                                | 17.8 us: 1.01x faster                                                       |
| unpickle_list              | 3.24 us                                                | 3.20 us: 1.01x faster                                                       |
| docutils                   | 1.54 sec                                               | 1.53 sec: 1.01x faster                                                      |
| scimark_monte_carlo        | 50.1 ms                                                | 49.5 ms: 1.01x faster                                                       |
| regex_effbot               | 2.59 ms                                                | 2.56 ms: 1.01x faster                                                       |
| coroutines                 | 18.1 ms                                                | 17.9 ms: 1.01x faster                                                       |
| json                       | 3.02 ms                                                | 3.00 ms: 1.01x faster                                                       |
| unpickle                   | 9.25 us                                                | 9.19 us: 1.01x faster                                                       |
| create_gc_cycles           | 704 us                                                 | 702 us: 1.00x faster                                                        |
| pidigits                   | 282 ms                                                 | 283 ms: 1.00x slower                                                        |
| sqlglot_normalize          | 188 ms                                                 | 188 ms: 1.00x slower                                                        |
| sympy_expand               | 249 ms                                                 | 250 ms: 1.00x slower                                                        |
| pickle                     | 7.42 us                                                | 7.46 us: 1.01x slower                                                       |
| sqlglot_optimize           | 34.7 ms                                                | 35.1 ms: 1.01x slower                                                       |
| dulwich_log                | 30.4 ms                                                | 30.8 ms: 1.01x slower                                                       |
| go                         | 107 ms                                                 | 109 ms: 1.01x slower                                                        |
| sympy_integrate            | 11.3 ms                                                | 11.5 ms: 1.02x slower                                                       |
| async_tree_cpu_io_mixed_tg | 535 ms                                                 | 546 ms: 1.02x slower                                                        |
| mdp                        | 1.66 sec                                               | 1.70 sec: 1.02x slower                                                      |
| async_tree_io_tg           | 673 ms                                                 | 692 ms: 1.03x slower                                                        |
| deltablue                  | 2.58 ms                                                | 2.66 ms: 1.03x slower                                                       |
| json_dumps                 | 6.46 ms                                                | 6.66 ms: 1.03x slower                                                       |
| xml_etree_iterparse        | 74.6 ms                                                | 76.8 ms: 1.03x slower                                                       |
| asyncio_tcp_ssl            | 1.26 sec                                               | 1.29 sec: 1.03x slower                                                      |
| bench_thread_pool          | 492 us                                                 | 507 us: 1.03x slower                                                        |
| async_generators           | 306 ms                                                 | 316 ms: 1.03x slower                                                        |
| sqlite_synth               | 1.59 us                                                | 1.64 us: 1.03x slower                                                       |
| xml_etree_process          | 38.7 ms                                                | 40.0 ms: 1.03x slower                                                       |
| logging_silent             | 68.3 ns                                                | 70.9 ns: 1.04x slower                                                       |
| float                      | 58.1 ms                                                | 60.3 ms: 1.04x slower                                                       |
| xml_etree_generate         | 55.9 ms                                                | 58.6 ms: 1.05x slower                                                       |
| pyflate                    | 329 ms                                                 | 345 ms: 1.05x slower                                                        |
| deepcopy_memo              | 24.6 us                                                | 25.8 us: 1.05x slower                                                       |
| async_tree_memoization_tg  | 320 ms                                                 | 336 ms: 1.05x slower                                                        |
| pycparser                  | 670 ms                                                 | 705 ms: 1.05x slower                                                        |
| chameleon                  | 4.51 ms                                                | 4.75 ms: 1.05x slower                                                       |
| python_startup             | 11.9 ms                                                | 12.6 ms: 1.05x slower                                                       |
| 2to3                       | 171 ms                                                 | 180 ms: 1.06x slower                                                        |
| richards_super             | 34.9 ms                                                | 37.0 ms: 1.06x slower                                                       |
| meteor_contest             | 73.3 ms                                                | 77.7 ms: 1.06x slower                                                       |
| async_tree_io              | 669 ms                                                 | 710 ms: 1.06x slower                                                        |
| scimark_lu                 | 71.5 ms                                                | 75.8 ms: 1.06x slower                                                       |
| async_tree_none_tg         | 254 ms                                                 | 270 ms: 1.06x slower                                                        |
| mako                       | 7.53 ms                                                | 8.00 ms: 1.06x slower                                                       |
| pickle_pure_python         | 188 us                                                 | 200 us: 1.06x slower                                                        |
| tomli_loads                | 1.39 sec                                               | 1.49 sec: 1.07x slower                                                      |
| pprint_pformat             | 1.00 sec                                               | 1.08 sec: 1.07x slower                                                      |
| pprint_safe_repr           | 491 ms                                                 | 528 ms: 1.08x slower                                                        |
| async_tree_memoization     | 309 ms                                                 | 334 ms: 1.08x slower                                                        |
| richards                   | 31.1 ms                                                | 33.6 ms: 1.08x slower                                                       |
| nqueens                    | 60.2 ms                                                | 65.2 ms: 1.08x slower                                                       |
| regex_v8                   | 15.7 ms                                                | 17.0 ms: 1.08x slower                                                       |
| regex_compile              | 75.6 ms                                                | 82.0 ms: 1.09x slower                                                       |
| scimark_sparse_mat_mult    | 3.14 ms                                                | 3.46 ms: 1.10x slower                                                       |
| scimark_fft                | 198 ms                                                 | 220 ms: 1.11x slower                                                        |
| scimark_sor                | 94.3 ms                                                | 107 ms: 1.13x slower                                                        |
| fannkuch                   | 265 ms                                                 | 299 ms: 1.13x slower                                                        |
| unpickle_pure_python       | 145 us                                                 | 164 us: 1.14x slower                                                        |
| python_startup_no_site     | 9.71 ms                                                | 11.2 ms: 1.15x slower                                                       |
| nbody                      | 68.5 ms                                                | 83.6 ms: 1.22x slower                                                       |
| telco                      | 3.79 ms                                                | 4.75 ms: 1.25x slower                                                       |
| coverage                   | 37.9 ms                                                | 48.6 ms: 1.28x slower                                                       |
| hexiom                     | 4.25 ms                                                | 5.55 ms: 1.30x slower                                                       |
| Geometric mean             | (ref)                                                  | 1.03x slower                                                                |

Benchmark hidden because not significant (11): asyncio_tcp, bench_mp_pool, pickle_list, asyncio_websockets, json_loads, gc_traversal, xml_etree_parse, async_tree_cpu_io_mixed, pathlib, mypy2, tornado_http
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
