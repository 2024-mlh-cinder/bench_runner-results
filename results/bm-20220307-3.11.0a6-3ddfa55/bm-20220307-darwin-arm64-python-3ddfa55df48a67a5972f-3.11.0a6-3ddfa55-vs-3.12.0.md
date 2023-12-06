
# Results vs. 3.12.0

- fork: python
- ref: 3ddfa55df48a67a5972f
- machine: darwin-arm64
- commit hash: 3ddfa55
- commit date: 2022-03-07
- overall geometric mean: 1.07x slower \*
- HPT reliability: 96.12%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220307-darwin-arm64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 171 ms                                                 | 164 ms: 1.04x faster                                                  |
| chameleon      | 4.51 ms                                                | 4.55 ms: 1.01x slower                                                 |
| docutils       | 1.54 sec                                               | 1.47 sec: 1.05x faster                                                |
| tornado_http   | 70.7 ms                                                | 73.8 ms: 1.04x slower                                                 |
| Geometric mean | (ref)                                                  | 1.01x faster                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220307-darwin-arm64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|----------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_cpu_io_mixed    | 525 ms                                                 | 533 ms: 1.01x slower                                                  |
| async_tree_io              | 669 ms                                                 | 704 ms: 1.05x slower                                                  |
| async_tree_none            | 262 ms                                                 | 287 ms: 1.10x slower                                                  |
| async_tree_memoization     | 309 ms                                                 | 347 ms: 1.12x slower                                                  |
| async_tree_io_tg           | 673 ms                                                 | 761 ms: 1.13x slower                                                  |
| async_tree_cpu_io_mixed_tg | 535 ms                                                 | 624 ms: 1.17x slower                                                  |
| async_tree_none_tg         | 254 ms                                                 | 350 ms: 1.38x slower                                                  |
| async_tree_memoization_tg  | 320 ms                                                 | 449 ms: 1.40x slower                                                  |
| Geometric mean             | (ref)                                                  | 1.16x slower                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220307-darwin-arm64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 58.1 ms                                                | 54.8 ms: 1.06x faster                                                 |
| pidigits       | 282 ms                                                 | 281 ms: 1.00x faster                                                  |
| nbody          | 68.5 ms                                                | 74.1 ms: 1.08x slower                                                 |
| Geometric mean | (ref)                                                  | 1.00x slower                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220307-darwin-arm64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_effbot   | 2.59 ms                                                | 2.45 ms: 1.06x faster                                                 |
| regex_compile  | 75.6 ms                                                | 76.7 ms: 1.01x slower                                                 |
| regex_v8       | 15.7 ms                                                | 17.5 ms: 1.12x slower                                                 |
| regex_dna      | 153 ms                                                 | 177 ms: 1.16x slower                                                  |
| Geometric mean | (ref)                                                  | 1.06x slower                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220307-darwin-arm64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| json_loads           | 17.6 us                                                | 14.9 us: 1.19x faster                                                 |
| unpickle_list        | 3.24 us                                                | 2.74 us: 1.18x faster                                                 |
| xml_etree_generate   | 55.9 ms                                                | 48.7 ms: 1.15x faster                                                 |
| xml_etree_parse      | 109 ms                                                 | 97.5 ms: 1.12x faster                                                 |
| unpickle             | 9.25 us                                                | 8.29 us: 1.12x faster                                                 |
| pickle_list          | 2.89 us                                                | 2.61 us: 1.11x faster                                                 |
| xml_etree_iterparse  | 74.6 ms                                                | 69.4 ms: 1.07x faster                                                 |
| xml_etree_process    | 38.7 ms                                                | 36.5 ms: 1.06x faster                                                 |
| pickle_dict          | 18.0 us                                                | 17.3 us: 1.04x faster                                                 |
| pickle               | 7.42 us                                                | 7.21 us: 1.03x faster                                                 |
| tomli_loads          | 1.39 sec                                               | 1.44 sec: 1.03x slower                                                |
| pickle_pure_python   | 188 us                                                 | 214 us: 1.14x slower                                                  |
| unpickle_pure_python | 145 us                                                 | 167 us: 1.16x slower                                                  |
| json_dumps           | 6.46 ms                                                | 7.66 ms: 1.19x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.04x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220307-darwin-arm64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 9.71 ms                                                | 9.28 ms: 1.05x faster                                                 |
| python_startup         | 11.9 ms                                                | 14.8 ms: 1.25x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.09x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220307-darwin-arm64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|-----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 7.53 ms                                                | 7.33 ms: 1.03x faster                                                 |
| django_template | 22.1 ms                                                | 21.6 ms: 1.03x faster                                                 |
| Geometric mean  | (ref)                                                  | 1.03x faster                                                          |

All benchmarks:
===============

| Benchmark                  | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220307-darwin-arm64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|----------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_generators           | 306 ms                                                 | 194 ms: 1.58x faster                                                  |
| sqlite_synth               | 1.59 us                                                | 1.25 us: 1.27x faster                                                 |
| pathlib                    | 29.3 ms                                                | 23.1 ms: 1.27x faster                                                 |
| json_loads                 | 17.6 us                                                | 14.9 us: 1.19x faster                                                 |
| unpickle_list              | 3.24 us                                                | 2.74 us: 1.18x faster                                                 |
| logging_format             | 3.99 us                                                | 3.43 us: 1.16x faster                                                 |
| logging_simple             | 3.69 us                                                | 3.21 us: 1.15x faster                                                 |
| raytrace                   | 246 ms                                                 | 214 ms: 1.15x faster                                                  |
| xml_etree_generate         | 55.9 ms                                                | 48.7 ms: 1.15x faster                                                 |
| telco                      | 3.79 ms                                                | 3.34 ms: 1.14x faster                                                 |
| scimark_monte_carlo        | 50.1 ms                                                | 44.6 ms: 1.12x faster                                                 |
| xml_etree_parse            | 109 ms                                                 | 97.5 ms: 1.12x faster                                                 |
| unpickle                   | 9.25 us                                                | 8.29 us: 1.12x faster                                                 |
| json                       | 3.02 ms                                                | 2.71 ms: 1.11x faster                                                 |
| pickle_list                | 2.89 us                                                | 2.61 us: 1.11x faster                                                 |
| sqlglot_normalize          | 188 ms                                                 | 170 ms: 1.11x faster                                                  |
| bench_mp_pool              | 46.3 ms                                                | 42.8 ms: 1.08x faster                                                 |
| sqlglot_optimize           | 34.7 ms                                                | 32.2 ms: 1.08x faster                                                 |
| xml_etree_iterparse        | 74.6 ms                                                | 69.4 ms: 1.07x faster                                                 |
| scimark_sor                | 94.3 ms                                                | 88.7 ms: 1.06x faster                                                 |
| float                      | 58.1 ms                                                | 54.8 ms: 1.06x faster                                                 |
| xml_etree_process          | 38.7 ms                                                | 36.5 ms: 1.06x faster                                                 |
| regex_effbot               | 2.59 ms                                                | 2.45 ms: 1.06x faster                                                 |
| docutils                   | 1.54 sec                                               | 1.47 sec: 1.05x faster                                                |
| deepcopy_reduce            | 2.05 us                                                | 1.95 us: 1.05x faster                                                 |
| python_startup_no_site     | 9.71 ms                                                | 9.28 ms: 1.05x faster                                                 |
| pickle_dict                | 18.0 us                                                | 17.3 us: 1.04x faster                                                 |
| pyflate                    | 329 ms                                                 | 316 ms: 1.04x faster                                                  |
| 2to3                       | 171 ms                                                 | 164 ms: 1.04x faster                                                  |
| nqueens                    | 60.2 ms                                                | 58.5 ms: 1.03x faster                                                 |
| pickle                     | 7.42 us                                                | 7.21 us: 1.03x faster                                                 |
| mako                       | 7.53 ms                                                | 7.33 ms: 1.03x faster                                                 |
| django_template            | 22.1 ms                                                | 21.6 ms: 1.03x faster                                                 |
| sqlalchemy_declarative     | 65.4 ms                                                | 63.8 ms: 1.02x faster                                                 |
| scimark_sparse_mat_mult    | 3.14 ms                                                | 3.07 ms: 1.02x faster                                                 |
| scimark_fft                | 198 ms                                                 | 194 ms: 1.02x faster                                                  |
| dulwich_log                | 30.4 ms                                                | 30.0 ms: 1.01x faster                                                 |
| sympy_expand               | 249 ms                                                 | 247 ms: 1.01x faster                                                  |
| sympy_str                  | 151 ms                                                 | 150 ms: 1.01x faster                                                  |
| pidigits                   | 282 ms                                                 | 281 ms: 1.00x faster                                                  |
| fannkuch                   | 265 ms                                                 | 264 ms: 1.00x faster                                                  |
| coroutines                 | 18.1 ms                                                | 18.1 ms: 1.00x faster                                                 |
| gc_traversal               | 2.40 ms                                                | 2.40 ms: 1.00x faster                                                 |
| chameleon                  | 4.51 ms                                                | 4.55 ms: 1.01x slower                                                 |
| meteor_contest             | 73.3 ms                                                | 74.1 ms: 1.01x slower                                                 |
| spectral_norm              | 74.6 ms                                                | 75.5 ms: 1.01x slower                                                 |
| async_tree_cpu_io_mixed    | 525 ms                                                 | 533 ms: 1.01x slower                                                  |
| regex_compile              | 75.6 ms                                                | 76.7 ms: 1.01x slower                                                 |
| deepcopy                   | 225 us                                                 | 229 us: 1.02x slower                                                  |
| create_gc_cycles           | 704 us                                                 | 720 us: 1.02x slower                                                  |
| sympy_sum                  | 79.5 ms                                                | 82.0 ms: 1.03x slower                                                 |
| tomli_loads                | 1.39 sec                                               | 1.44 sec: 1.03x slower                                                |
| bench_thread_pool          | 492 us                                                 | 510 us: 1.04x slower                                                  |
| sympy_integrate            | 11.3 ms                                                | 11.7 ms: 1.04x slower                                                 |
| go                         | 107 ms                                                 | 112 ms: 1.04x slower                                                  |
| tornado_http               | 70.7 ms                                                | 73.8 ms: 1.04x slower                                                 |
| async_tree_io              | 669 ms                                                 | 704 ms: 1.05x slower                                                  |
| chaos                      | 44.8 ms                                                | 47.2 ms: 1.05x slower                                                 |
| scimark_lu                 | 71.5 ms                                                | 75.5 ms: 1.06x slower                                                 |
| pycparser                  | 670 ms                                                 | 711 ms: 1.06x slower                                                  |
| crypto_pyaes               | 52.0 ms                                                | 55.4 ms: 1.06x slower                                                 |
| nbody                      | 68.5 ms                                                | 74.1 ms: 1.08x slower                                                 |
| mdp                        | 1.66 sec                                               | 1.80 sec: 1.08x slower                                                |
| comprehensions             | 15.8 us                                                | 17.1 us: 1.08x slower                                                 |
| generators                 | 28.3 ms                                                | 30.8 ms: 1.09x slower                                                 |
| pprint_safe_repr           | 491 ms                                                 | 538 ms: 1.09x slower                                                  |
| async_tree_none            | 262 ms                                                 | 287 ms: 1.10x slower                                                  |
| pprint_pformat             | 1.00 sec                                               | 1.10 sec: 1.10x slower                                                |
| sqlalchemy_imperative      | 6.92 ms                                                | 7.72 ms: 1.12x slower                                                 |
| regex_v8                   | 15.7 ms                                                | 17.5 ms: 1.12x slower                                                 |
| deepcopy_memo              | 24.6 us                                                | 27.5 us: 1.12x slower                                                 |
| async_tree_memoization     | 309 ms                                                 | 347 ms: 1.12x slower                                                  |
| richards                   | 31.1 ms                                                | 34.9 ms: 1.12x slower                                                 |
| hexiom                     | 4.25 ms                                                | 4.78 ms: 1.12x slower                                                 |
| async_tree_io_tg           | 673 ms                                                 | 761 ms: 1.13x slower                                                  |
| pickle_pure_python         | 188 us                                                 | 214 us: 1.14x slower                                                  |
| asyncio_tcp_ssl            | 1.26 sec                                               | 1.44 sec: 1.14x slower                                                |
| unpickle_pure_python       | 145 us                                                 | 167 us: 1.16x slower                                                  |
| regex_dna                  | 153 ms                                                 | 177 ms: 1.16x slower                                                  |
| async_tree_cpu_io_mixed_tg | 535 ms                                                 | 624 ms: 1.17x slower                                                  |
| deltablue                  | 2.58 ms                                                | 3.03 ms: 1.17x slower                                                 |
| logging_silent             | 68.3 ns                                                | 80.3 ns: 1.17x slower                                                 |
| json_dumps                 | 6.46 ms                                                | 7.66 ms: 1.19x slower                                                 |
| richards_super             | 34.9 ms                                                | 41.9 ms: 1.20x slower                                                 |
| python_startup             | 11.9 ms                                                | 14.8 ms: 1.25x slower                                                 |
| sqlglot_transpile          | 1.08 ms                                                | 1.40 ms: 1.30x slower                                                 |
| dask                       | 228 ms                                                 | 308 ms: 1.35x slower                                                  |
| sqlglot_parse              | 897 us                                                 | 1.23 ms: 1.37x slower                                                 |
| async_tree_none_tg         | 254 ms                                                 | 350 ms: 1.38x slower                                                  |
| async_tree_memoization_tg  | 320 ms                                                 | 449 ms: 1.40x slower                                                  |
| asyncio_tcp                | 450 ms                                                 | 663 ms: 1.47x slower                                                  |
| unpack_sequence            | 28.4 ns                                                | 93.6 ns: 3.30x slower                                                 |
| typing_runtime_protocols   | 90.8 us                                                | 330 us: 3.64x slower                                                  |
| coverage                   | 37.9 ms                                                | 328 ms: 8.64x slower                                                  |
| Geometric mean             | (ref)                                                  | 1.07x slower                                                          |

Benchmark hidden because not significant (2): aiohttp, gunicorn
Ignored benchmarks (2) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: asyncio_websockets, mypy2
Ignored benchmarks (6) of results/bm-20220307-3.11.0a6-3ddfa55/bm-20220307-darwin-arm64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 96.12% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
