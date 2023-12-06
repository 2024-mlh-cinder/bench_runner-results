
# Results vs. 3.11.0

- fork: python
- ref: 3ddfa55df48a67a5972f
- machine: darwin-arm64
- commit hash: 3ddfa55
- commit date: 2022-03-07
- overall geometric mean: 1.08x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20220307-darwin-arm64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 155 ms                                                 | 164 ms: 1.06x slower                                                  |
| chameleon      | 4.17 ms                                                | 4.55 ms: 1.09x slower                                                 |
| docutils       | 1.46 sec                                               | 1.47 sec: 1.01x slower                                                |
| tornado_http   | 71.0 ms                                                | 73.8 ms: 1.04x slower                                                 |
| Geometric mean | (ref)                                                  | 1.04x slower                                                          |

Benchmark hidden because not significant (1): html5lib

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20220307-darwin-arm64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|----------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_memoization     | 361 ms                                                 | 347 ms: 1.04x faster                                                  |
| async_tree_none            | 282 ms                                                 | 287 ms: 1.02x slower                                                  |
| async_tree_cpu_io_mixed    | 522 ms                                                 | 533 ms: 1.02x slower                                                  |
| async_tree_io_tg           | 734 ms                                                 | 761 ms: 1.04x slower                                                  |
| async_tree_cpu_io_mixed_tg | 554 ms                                                 | 624 ms: 1.13x slower                                                  |
| async_tree_none_tg         | 280 ms                                                 | 350 ms: 1.25x slower                                                  |
| async_tree_memoization_tg  | 357 ms                                                 | 449 ms: 1.26x slower                                                  |
| Geometric mean             | (ref)                                                  | 1.08x slower                                                          |

Benchmark hidden because not significant (1): async_tree_io

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20220307-darwin-arm64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 55.4 ms                                                | 54.8 ms: 1.01x faster                                                 |
| nbody          | 68.7 ms                                                | 74.1 ms: 1.08x slower                                                 |
| Geometric mean | (ref)                                                  | 1.02x slower                                                          |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20220307-darwin-arm64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_effbot   | 2.46 ms                                                | 2.45 ms: 1.00x faster                                                 |
| regex_compile  | 73.9 ms                                                | 76.7 ms: 1.04x slower                                                 |
| regex_v8       | 15.3 ms                                                | 17.5 ms: 1.14x slower                                                 |
| regex_dna      | 149 ms                                                 | 177 ms: 1.19x slower                                                  |
| Geometric mean | (ref)                                                  | 1.09x slower                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20220307-darwin-arm64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| xml_etree_parse      | 107 ms                                                 | 97.5 ms: 1.10x faster                                                 |
| json_loads           | 15.8 us                                                | 14.9 us: 1.06x faster                                                 |
| pickle_list          | 2.67 us                                                | 2.61 us: 1.02x faster                                                 |
| unpickle_list        | 2.77 us                                                | 2.74 us: 1.01x faster                                                 |
| unpickle             | 8.32 us                                                | 8.29 us: 1.00x faster                                                 |
| json_dumps           | 7.58 ms                                                | 7.66 ms: 1.01x slower                                                 |
| pickle_dict          | 17.0 us                                                | 17.3 us: 1.01x slower                                                 |
| pickle_pure_python   | 211 us                                                 | 214 us: 1.02x slower                                                  |
| xml_etree_iterparse  | 68.2 ms                                                | 69.4 ms: 1.02x slower                                                 |
| unpickle_pure_python | 163 us                                                 | 167 us: 1.02x slower                                                  |
| xml_etree_generate   | 46.8 ms                                                | 48.7 ms: 1.04x slower                                                 |
| xml_etree_process    | 34.0 ms                                                | 36.5 ms: 1.07x slower                                                 |
| tomli_loads          | 1.30 sec                                               | 1.44 sec: 1.10x slower                                                |
| Geometric mean       | (ref)                                                  | 1.01x slower                                                          |

Benchmark hidden because not significant (1): pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20220307-darwin-arm64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 9.15 ms                                                | 9.28 ms: 1.01x slower                                                 |
| python_startup         | 11.4 ms                                                | 14.8 ms: 1.31x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.15x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20220307-darwin-arm64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|-----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 8.22 ms                                                | 7.33 ms: 1.12x faster                                                 |
| genshi_text     | 14.5 ms                                                | 15.2 ms: 1.05x slower                                                 |
| django_template | 19.8 ms                                                | 21.6 ms: 1.09x slower                                                 |
| genshi_xml      | 28.1 ms                                                | 31.4 ms: 1.11x slower                                                 |
| Geometric mean  | (ref)                                                  | 1.03x slower                                                          |

All benchmarks:
===============

| Benchmark                  | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20220307-darwin-arm64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|----------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pathlib                    | 28.5 ms                                                | 23.1 ms: 1.23x faster                                                 |
| mako                       | 8.22 ms                                                | 7.33 ms: 1.12x faster                                                 |
| xml_etree_parse            | 107 ms                                                 | 97.5 ms: 1.10x faster                                                 |
| sqlite_synth               | 1.35 us                                                | 1.25 us: 1.08x faster                                                 |
| logging_format             | 3.69 us                                                | 3.43 us: 1.08x faster                                                 |
| logging_simple             | 3.41 us                                                | 3.21 us: 1.06x faster                                                 |
| json_loads                 | 15.8 us                                                | 14.9 us: 1.06x faster                                                 |
| scimark_monte_carlo        | 47.1 ms                                                | 44.6 ms: 1.06x faster                                                 |
| deepcopy_memo              | 28.9 us                                                | 27.5 us: 1.05x faster                                                 |
| async_tree_memoization     | 361 ms                                                 | 347 ms: 1.04x faster                                                  |
| pylint                     | 256 ms                                                 | 247 ms: 1.04x faster                                                  |
| json                       | 2.77 ms                                                | 2.71 ms: 1.02x faster                                                 |
| chaos                      | 48.2 ms                                                | 47.2 ms: 1.02x faster                                                 |
| pickle_list                | 2.67 us                                                | 2.61 us: 1.02x faster                                                 |
| deepcopy                   | 233 us                                                 | 229 us: 1.02x faster                                                  |
| deepcopy_reduce            | 1.98 us                                                | 1.95 us: 1.01x faster                                                 |
| float                      | 55.4 ms                                                | 54.8 ms: 1.01x faster                                                 |
| unpickle_list              | 2.77 us                                                | 2.74 us: 1.01x faster                                                 |
| meteor_contest             | 74.9 ms                                                | 74.1 ms: 1.01x faster                                                 |
| flaskblogging              | 2.46 ms                                                | 2.43 ms: 1.01x faster                                                 |
| unpickle                   | 8.32 us                                                | 8.29 us: 1.00x faster                                                 |
| regex_effbot               | 2.46 ms                                                | 2.45 ms: 1.00x faster                                                 |
| dulwich_log                | 29.9 ms                                                | 30.0 ms: 1.00x slower                                                 |
| gc_traversal               | 2.39 ms                                                | 2.40 ms: 1.00x slower                                                 |
| sympy_sum                  | 81.6 ms                                                | 82.0 ms: 1.01x slower                                                 |
| create_gc_cycles           | 715 us                                                 | 720 us: 1.01x slower                                                  |
| docutils                   | 1.46 sec                                               | 1.47 sec: 1.01x slower                                                |
| async_generators           | 192 ms                                                 | 194 ms: 1.01x slower                                                  |
| json_dumps                 | 7.58 ms                                                | 7.66 ms: 1.01x slower                                                 |
| pickle_dict                | 17.0 us                                                | 17.3 us: 1.01x slower                                                 |
| python_startup_no_site     | 9.15 ms                                                | 9.28 ms: 1.01x slower                                                 |
| async_tree_none            | 282 ms                                                 | 287 ms: 1.02x slower                                                  |
| pickle_pure_python         | 211 us                                                 | 214 us: 1.02x slower                                                  |
| xml_etree_iterparse        | 68.2 ms                                                | 69.4 ms: 1.02x slower                                                 |
| async_tree_cpu_io_mixed    | 522 ms                                                 | 533 ms: 1.02x slower                                                  |
| scimark_sparse_mat_mult    | 3.01 ms                                                | 3.07 ms: 1.02x slower                                                 |
| asyncio_tcp                | 650 ms                                                 | 663 ms: 1.02x slower                                                  |
| thrift                     | 424 us                                                 | 433 us: 1.02x slower                                                  |
| bench_mp_pool              | 41.9 ms                                                | 42.8 ms: 1.02x slower                                                 |
| typing_runtime_protocols   | 323 us                                                 | 330 us: 1.02x slower                                                  |
| unpickle_pure_python       | 163 us                                                 | 167 us: 1.02x slower                                                  |
| mdp                        | 1.73 sec                                               | 1.80 sec: 1.04x slower                                                |
| sympy_integrate            | 11.3 ms                                                | 11.7 ms: 1.04x slower                                                 |
| async_tree_io_tg           | 734 ms                                                 | 761 ms: 1.04x slower                                                  |
| regex_compile              | 73.9 ms                                                | 76.7 ms: 1.04x slower                                                 |
| scimark_fft                | 187 ms                                                 | 194 ms: 1.04x slower                                                  |
| tornado_http               | 71.0 ms                                                | 73.8 ms: 1.04x slower                                                 |
| xml_etree_generate         | 46.8 ms                                                | 48.7 ms: 1.04x slower                                                 |
| sympy_str                  | 144 ms                                                 | 150 ms: 1.04x slower                                                  |
| hexiom                     | 4.55 ms                                                | 4.78 ms: 1.05x slower                                                 |
| genshi_text                | 14.5 ms                                                | 15.2 ms: 1.05x slower                                                 |
| telco                      | 3.17 ms                                                | 3.34 ms: 1.05x slower                                                 |
| generators                 | 29.2 ms                                                | 30.8 ms: 1.05x slower                                                 |
| sqlalchemy_declarative     | 60.6 ms                                                | 63.8 ms: 1.05x slower                                                 |
| sympy_expand               | 234 ms                                                 | 247 ms: 1.06x slower                                                  |
| 2to3                       | 155 ms                                                 | 164 ms: 1.06x slower                                                  |
| aiohttp                    | 1.05 ms                                                | 1.12 ms: 1.06x slower                                                 |
| sqlglot_normalize          | 160 ms                                                 | 170 ms: 1.06x slower                                                  |
| pyflate                    | 297 ms                                                 | 316 ms: 1.06x slower                                                  |
| raytrace                   | 200 ms                                                 | 214 ms: 1.07x slower                                                  |
| pycparser                  | 667 ms                                                 | 711 ms: 1.07x slower                                                  |
| fannkuch                   | 247 ms                                                 | 264 ms: 1.07x slower                                                  |
| nqueens                    | 54.6 ms                                                | 58.5 ms: 1.07x slower                                                 |
| xml_etree_process          | 34.0 ms                                                | 36.5 ms: 1.07x slower                                                 |
| sqlalchemy_imperative      | 7.17 ms                                                | 7.72 ms: 1.08x slower                                                 |
| nbody                      | 68.7 ms                                                | 74.1 ms: 1.08x slower                                                 |
| spectral_norm              | 69.7 ms                                                | 75.5 ms: 1.08x slower                                                 |
| sqlglot_optimize           | 29.6 ms                                                | 32.2 ms: 1.09x slower                                                 |
| gunicorn                   | 1.11 ms                                                | 1.21 ms: 1.09x slower                                                 |
| chameleon                  | 4.17 ms                                                | 4.55 ms: 1.09x slower                                                 |
| coroutines                 | 16.6 ms                                                | 18.1 ms: 1.09x slower                                                 |
| django_template            | 19.8 ms                                                | 21.6 ms: 1.09x slower                                                 |
| go                         | 102 ms                                                 | 112 ms: 1.09x slower                                                  |
| tomli_loads                | 1.30 sec                                               | 1.44 sec: 1.10x slower                                                |
| bench_thread_pool          | 461 us                                                 | 510 us: 1.11x slower                                                  |
| scimark_lu                 | 67.8 ms                                                | 75.5 ms: 1.11x slower                                                 |
| genshi_xml                 | 28.1 ms                                                | 31.4 ms: 1.11x slower                                                 |
| pprint_pformat             | 989 ms                                                 | 1.10 sec: 1.12x slower                                                |
| pprint_safe_repr           | 479 ms                                                 | 538 ms: 1.12x slower                                                  |
| deltablue                  | 2.70 ms                                                | 3.03 ms: 1.12x slower                                                 |
| async_tree_cpu_io_mixed_tg | 554 ms                                                 | 624 ms: 1.13x slower                                                  |
| richards                   | 30.8 ms                                                | 34.9 ms: 1.14x slower                                                 |
| richards_super             | 36.8 ms                                                | 41.9 ms: 1.14x slower                                                 |
| regex_v8                   | 15.3 ms                                                | 17.5 ms: 1.14x slower                                                 |
| crypto_pyaes               | 48.1 ms                                                | 55.4 ms: 1.15x slower                                                 |
| comprehensions             | 14.7 us                                                | 17.1 us: 1.16x slower                                                 |
| scimark_sor                | 75.2 ms                                                | 88.7 ms: 1.18x slower                                                 |
| regex_dna                  | 149 ms                                                 | 177 ms: 1.19x slower                                                  |
| logging_silent             | 64.5 ns                                                | 80.3 ns: 1.25x slower                                                 |
| async_tree_none_tg         | 280 ms                                                 | 350 ms: 1.25x slower                                                  |
| async_tree_memoization_tg  | 357 ms                                                 | 449 ms: 1.26x slower                                                  |
| python_startup             | 11.4 ms                                                | 14.8 ms: 1.31x slower                                                 |
| sqlglot_transpile          | 1.05 ms                                                | 1.40 ms: 1.33x slower                                                 |
| dask                       | 224 ms                                                 | 308 ms: 1.38x slower                                                  |
| sqlglot_parse              | 886 us                                                 | 1.23 ms: 1.39x slower                                                 |
| unpack_sequence            | 32.3 ns                                                | 93.6 ns: 2.90x slower                                                 |
| coverage                   | 41.4 ms                                                | 328 ms: 7.92x slower                                                  |
| Geometric mean             | (ref)                                                  | 1.08x slower                                                          |

Benchmark hidden because not significant (5): html5lib, asyncio_tcp_ssl, pidigits, pickle, async_tree_io
Ignored benchmarks (2) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: asyncio_websockets, mypy2


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.03x
