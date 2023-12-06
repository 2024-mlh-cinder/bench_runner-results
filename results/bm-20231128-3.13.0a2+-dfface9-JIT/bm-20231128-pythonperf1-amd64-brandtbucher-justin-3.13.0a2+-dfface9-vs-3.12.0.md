
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: dfface9
- commit date: 2023-11-28
- overall geometric mean: 1.05x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-pythonperf1-amd64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 233 ms: 1.10x slower                                                |
| chameleon      | 4.95 ms                                                     | 5.29 ms: 1.07x slower                                               |
| docutils       | 1.61 sec                                                    | 1.66 sec: 1.03x slower                                              |
| tornado_http   | 87.2 ms                                                     | 93.3 ms: 1.07x slower                                               |
| Geometric mean | (ref)                                                       | 1.07x slower                                                        |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-pythonperf1-amd64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| async_tree_cpu_io_mixed_tg | 483 ms                                                      | 517 ms: 1.07x slower                                                |
| async_tree_none_tg         | 277 ms                                                      | 298 ms: 1.08x slower                                                |
| async_tree_memoization     | 333 ms                                                      | 359 ms: 1.08x slower                                                |
| async_tree_io              | 712 ms                                                      | 775 ms: 1.09x slower                                                |
| async_tree_io_tg           | 742 ms                                                      | 816 ms: 1.10x slower                                                |
| async_tree_memoization_tg  | 345 ms                                                      | 384 ms: 1.11x slower                                                |
| Geometric mean             | (ref)                                                       | 1.07x slower                                                        |

Benchmark hidden because not significant (2): async_tree_none, async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-pythonperf1-amd64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| nbody          | 68.8 ms                                                     | 60.1 ms: 1.14x faster                                               |
| float          | 54.7 ms                                                     | 50.0 ms: 1.09x faster                                               |
| pidigits       | 150 ms                                                      | 150 ms: 1.00x slower                                                |
| Geometric mean | (ref)                                                       | 1.08x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-pythonperf1-amd64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 87.2 ms                                                     | 87.7 ms: 1.01x slower                                               |
| regex_dna      | 119 ms                                                      | 124 ms: 1.04x slower                                                |
| regex_effbot   | 1.58 ms                                                     | 1.79 ms: 1.13x slower                                               |
| regex_v8       | 13.5 ms                                                     | 21.3 ms: 1.58x slower                                               |
| Geometric mean | (ref)                                                       | 1.17x slower                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-pythonperf1-amd64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| pickle               | 7.38 us                                                     | 7.11 us: 1.04x faster                                               |
| unpickle             | 8.44 us                                                     | 8.23 us: 1.03x faster                                               |
| pickle_pure_python   | 195 us                                                      | 193 us: 1.01x faster                                                |
| xml_etree_iterparse  | 63.1 ms                                                     | 64.9 ms: 1.03x slower                                               |
| xml_etree_generate   | 55.8 ms                                                     | 58.0 ms: 1.04x slower                                               |
| json_dumps           | 5.83 ms                                                     | 6.13 ms: 1.05x slower                                               |
| xml_etree_process    | 37.6 ms                                                     | 39.7 ms: 1.05x slower                                               |
| xml_etree_parse      | 90.5 ms                                                     | 96.0 ms: 1.06x slower                                               |
| json_loads           | 13.6 us                                                     | 14.5 us: 1.06x slower                                               |
| unpickle_pure_python | 134 us                                                      | 147 us: 1.09x slower                                                |
| pickle_list          | 2.88 us                                                     | 3.26 us: 1.13x slower                                               |
| Geometric mean       | (ref)                                                       | 1.03x slower                                                        |

Benchmark hidden because not significant (3): unpickle_list, tomli_loads, pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-pythonperf1-amd64-brandtbucher-justin-3.13.0a2+-dfface9 |
|------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.8 ms: 1.10x slower                                               |
| python_startup_no_site | 15.9 ms                                                     | 18.9 ms: 1.18x slower                                               |
| Geometric mean         | (ref)                                                       | 1.14x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-pythonperf1-amd64-brandtbucher-justin-3.13.0a2+-dfface9 |
|-----------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 6.37 ms: 1.11x faster                                               |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-pythonperf1-amd64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| comprehensions             | 14.0 us                                                     | 11.8 us: 1.18x faster                                               |
| typing_runtime_protocols   | 96.7 us                                                     | 82.7 us: 1.17x faster                                               |
| nbody                      | 68.8 ms                                                     | 60.1 ms: 1.14x faster                                               |
| mako                       | 7.05 ms                                                     | 6.37 ms: 1.11x faster                                               |
| float                      | 54.7 ms                                                     | 50.0 ms: 1.09x faster                                               |
| sqlite_synth               | 1.75 us                                                     | 1.60 us: 1.09x faster                                               |
| raytrace                   | 192 ms                                                      | 177 ms: 1.09x faster                                                |
| asyncio_tcp_ssl            | 1.89 sec                                                    | 1.77 sec: 1.06x faster                                              |
| pickle                     | 7.38 us                                                     | 7.11 us: 1.04x faster                                               |
| sympy_sum                  | 90.1 ms                                                     | 87.8 ms: 1.03x faster                                               |
| unpickle                   | 8.44 us                                                     | 8.23 us: 1.03x faster                                               |
| deltablue                  | 2.12 ms                                                     | 2.09 ms: 1.01x faster                                               |
| pickle_pure_python         | 195 us                                                      | 193 us: 1.01x faster                                                |
| mdp                        | 1.42 sec                                                    | 1.41 sec: 1.00x faster                                              |
| pidigits                   | 150 ms                                                      | 150 ms: 1.00x slower                                                |
| regex_compile              | 87.2 ms                                                     | 87.7 ms: 1.01x slower                                               |
| crypto_pyaes               | 46.4 ms                                                     | 46.8 ms: 1.01x slower                                               |
| deepcopy_memo              | 23.4 us                                                     | 23.8 us: 1.02x slower                                               |
| logging_format             | 6.72 us                                                     | 6.82 us: 1.02x slower                                               |
| gc_traversal               | 1.49 ms                                                     | 1.53 ms: 1.03x slower                                               |
| xml_etree_iterparse        | 63.1 ms                                                     | 64.9 ms: 1.03x slower                                               |
| pathlib                    | 79.6 ms                                                     | 82.0 ms: 1.03x slower                                               |
| richards_super             | 31.2 ms                                                     | 32.1 ms: 1.03x slower                                               |
| spectral_norm              | 63.9 ms                                                     | 65.9 ms: 1.03x slower                                               |
| richards                   | 27.6 ms                                                     | 28.5 ms: 1.03x slower                                               |
| docutils                   | 1.61 sec                                                    | 1.66 sec: 1.03x slower                                              |
| create_gc_cycles           | 726 us                                                      | 752 us: 1.04x slower                                                |
| chaos                      | 42.1 ms                                                     | 43.7 ms: 1.04x slower                                               |
| pyflate                    | 294 ms                                                      | 305 ms: 1.04x slower                                                |
| unpack_sequence            | 36.9 ns                                                     | 38.3 ns: 1.04x slower                                               |
| xml_etree_generate         | 55.8 ms                                                     | 58.0 ms: 1.04x slower                                               |
| sympy_expand               | 278 ms                                                      | 289 ms: 1.04x slower                                                |
| regex_dna                  | 119 ms                                                      | 124 ms: 1.04x slower                                                |
| logging_simple             | 6.21 us                                                     | 6.48 us: 1.04x slower                                               |
| scimark_lu                 | 57.5 ms                                                     | 60.3 ms: 1.05x slower                                               |
| fannkuch                   | 244 ms                                                      | 256 ms: 1.05x slower                                                |
| json_dumps                 | 5.83 ms                                                     | 6.13 ms: 1.05x slower                                               |
| coroutines                 | 14.1 ms                                                     | 14.8 ms: 1.05x slower                                               |
| scimark_sor                | 79.8 ms                                                     | 83.9 ms: 1.05x slower                                               |
| deepcopy_reduce            | 2.08 us                                                     | 2.19 us: 1.05x slower                                               |
| asyncio_tcp                | 471 ms                                                      | 496 ms: 1.05x slower                                                |
| xml_etree_process          | 37.6 ms                                                     | 39.7 ms: 1.05x slower                                               |
| dulwich_log                | 42.7 ms                                                     | 45.1 ms: 1.06x slower                                               |
| logging_silent             | 60.5 ns                                                     | 64.0 ns: 1.06x slower                                               |
| scimark_fft                | 181 ms                                                      | 192 ms: 1.06x slower                                                |
| sympy_integrate            | 13.0 ms                                                     | 13.7 ms: 1.06x slower                                               |
| xml_etree_parse            | 90.5 ms                                                     | 96.0 ms: 1.06x slower                                               |
| deepcopy                   | 233 us                                                      | 247 us: 1.06x slower                                                |
| bench_thread_pool          | 830 us                                                      | 882 us: 1.06x slower                                                |
| json_loads                 | 13.6 us                                                     | 14.5 us: 1.06x slower                                               |
| scimark_sparse_mat_mult    | 2.51 ms                                                     | 2.67 ms: 1.06x slower                                               |
| json                       | 2.94 ms                                                     | 3.14 ms: 1.07x slower                                               |
| meteor_contest             | 72.1 ms                                                     | 76.9 ms: 1.07x slower                                               |
| async_tree_cpu_io_mixed_tg | 483 ms                                                      | 517 ms: 1.07x slower                                                |
| chameleon                  | 4.95 ms                                                     | 5.29 ms: 1.07x slower                                               |
| nqueens                    | 61.7 ms                                                     | 66.0 ms: 1.07x slower                                               |
| tornado_http               | 87.2 ms                                                     | 93.3 ms: 1.07x slower                                               |
| pprint_pformat             | 1.04 sec                                                    | 1.11 sec: 1.07x slower                                              |
| sqlglot_parse              | 802 us                                                      | 862 us: 1.08x slower                                                |
| go                         | 89.0 ms                                                     | 95.8 ms: 1.08x slower                                               |
| async_tree_none_tg         | 277 ms                                                      | 298 ms: 1.08x slower                                                |
| async_tree_memoization     | 333 ms                                                      | 359 ms: 1.08x slower                                                |
| sqlglot_optimize           | 34.0 ms                                                     | 36.7 ms: 1.08x slower                                               |
| pprint_safe_repr           | 508 ms                                                      | 548 ms: 1.08x slower                                                |
| sqlglot_normalize          | 183 ms                                                      | 198 ms: 1.08x slower                                                |
| dask                       | 255 ms                                                      | 276 ms: 1.08x slower                                                |
| sqlglot_transpile          | 1.02 ms                                                     | 1.10 ms: 1.08x slower                                               |
| async_tree_io              | 712 ms                                                      | 775 ms: 1.09x slower                                                |
| unpickle_pure_python       | 134 us                                                      | 147 us: 1.09x slower                                                |
| hexiom                     | 4.00 ms                                                     | 4.38 ms: 1.09x slower                                               |
| 2to3                       | 213 ms                                                      | 233 ms: 1.10x slower                                                |
| async_tree_io_tg           | 742 ms                                                      | 816 ms: 1.10x slower                                                |
| python_startup             | 18.8 ms                                                     | 20.8 ms: 1.10x slower                                               |
| pycparser                  | 673 ms                                                      | 747 ms: 1.11x slower                                                |
| async_generators           | 230 ms                                                      | 255 ms: 1.11x slower                                                |
| scimark_monte_carlo        | 43.0 ms                                                     | 47.7 ms: 1.11x slower                                               |
| async_tree_memoization_tg  | 345 ms                                                      | 384 ms: 1.11x slower                                                |
| pickle_list                | 2.88 us                                                     | 3.26 us: 1.13x slower                                               |
| regex_effbot               | 1.58 ms                                                     | 1.79 ms: 1.13x slower                                               |
| generators                 | 22.6 ms                                                     | 25.7 ms: 1.14x slower                                               |
| telco                      | 4.08 ms                                                     | 4.78 ms: 1.17x slower                                               |
| coverage                   | 39.8 ms                                                     | 47.0 ms: 1.18x slower                                               |
| python_startup_no_site     | 15.9 ms                                                     | 18.9 ms: 1.18x slower                                               |
| regex_v8                   | 13.5 ms                                                     | 21.3 ms: 1.58x slower                                               |
| mypy2                      | 209 ms                                                      | 450 ms: 2.15x slower                                                |
| Geometric mean             | (ref)                                                       | 1.05x slower                                                        |

Benchmark hidden because not significant (7): async_tree_none, unpickle_list, bench_mp_pool, tomli_loads, pickle_dict, sympy_str, async_tree_cpu_io_mixed
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.04x
- 95% likely to have a slowdown of 1.04x
- 99% likely to have a slowdown of 1.03x
