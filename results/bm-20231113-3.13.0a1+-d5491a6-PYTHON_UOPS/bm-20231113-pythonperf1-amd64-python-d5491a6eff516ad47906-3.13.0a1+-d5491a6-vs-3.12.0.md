
# Results vs. 3.12.0

- fork: python
- ref: d5491a6eff516ad47906
- machine: windows-amd64
- commit hash: d5491a6
- commit date: 2023-11-13
- overall geometric mean: 1.06x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 223 ms: 1.05x slower                                                        |
| chameleon      | 4.95 ms                                                     | 5.09 ms: 1.03x slower                                                       |
| tornado_http   | 87.2 ms                                                     | 89.8 ms: 1.03x slower                                                       |
| Geometric mean | (ref)                                                       | 1.03x slower                                                                |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none            | 286 ms                                                      | 279 ms: 1.02x faster                                                        |
| async_tree_cpu_io_mixed    | 477 ms                                                      | 468 ms: 1.02x faster                                                        |
| async_tree_cpu_io_mixed_tg | 483 ms                                                      | 492 ms: 1.02x slower                                                        |
| async_tree_io              | 712 ms                                                      | 734 ms: 1.03x slower                                                        |
| async_tree_io_tg           | 742 ms                                                      | 783 ms: 1.05x slower                                                        |
| async_tree_none_tg         | 277 ms                                                      | 293 ms: 1.06x slower                                                        |
| async_tree_memoization     | 333 ms                                                      | 354 ms: 1.06x slower                                                        |
| async_tree_memoization_tg  | 345 ms                                                      | 375 ms: 1.09x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.03x slower                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 147 ms: 1.02x faster                                                        |
| float          | 54.7 ms                                                     | 66.0 ms: 1.21x slower                                                       |
| nbody          | 68.8 ms                                                     | 86.6 ms: 1.26x slower                                                       |
| Geometric mean | (ref)                                                       | 1.14x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_effbot   | 1.58 ms                                                     | 1.56 ms: 1.02x faster                                                       |
| regex_dna      | 119 ms                                                      | 118 ms: 1.01x faster                                                        |
| regex_compile  | 87.2 ms                                                     | 95.5 ms: 1.09x slower                                                       |
| regex_v8       | 13.5 ms                                                     | 15.0 ms: 1.11x slower                                                       |
| Geometric mean | (ref)                                                       | 1.04x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_pure_python   | 195 us                                                      | 182 us: 1.07x faster                                                        |
| pickle               | 7.38 us                                                     | 7.01 us: 1.05x faster                                                       |
| unpickle_list        | 2.69 us                                                     | 2.60 us: 1.04x faster                                                       |
| pickle_dict          | 18.9 us                                                     | 18.3 us: 1.03x faster                                                       |
| unpickle             | 8.44 us                                                     | 8.27 us: 1.02x faster                                                       |
| json_loads           | 13.6 us                                                     | 13.4 us: 1.02x faster                                                       |
| json_dumps           | 5.83 ms                                                     | 5.73 ms: 1.02x faster                                                       |
| xml_etree_process    | 37.6 ms                                                     | 37.1 ms: 1.01x faster                                                       |
| xml_etree_generate   | 55.8 ms                                                     | 55.0 ms: 1.01x faster                                                       |
| pickle_list          | 2.88 us                                                     | 2.85 us: 1.01x faster                                                       |
| xml_etree_parse      | 90.5 ms                                                     | 92.8 ms: 1.03x slower                                                       |
| xml_etree_iterparse  | 63.1 ms                                                     | 68.7 ms: 1.09x slower                                                       |
| unpickle_pure_python | 134 us                                                      | 147 us: 1.10x slower                                                        |
| tomli_loads          | 1.38 sec                                                    | 1.75 sec: 1.27x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.01x slower                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 19.7 ms: 1.04x slower                                                       |
| python_startup_no_site | 15.9 ms                                                     | 18.1 ms: 1.14x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.09x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 8.56 ms: 1.21x slower                                                       |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols   | 96.7 us                                                     | 79.2 us: 1.22x faster                                                       |
| sqlite_synth               | 1.75 us                                                     | 1.58 us: 1.10x faster                                                       |
| raytrace                   | 192 ms                                                      | 178 ms: 1.08x faster                                                        |
| pickle_pure_python         | 195 us                                                      | 182 us: 1.07x faster                                                        |
| generators                 | 22.6 ms                                                     | 21.2 ms: 1.07x faster                                                       |
| deepcopy_reduce            | 2.08 us                                                     | 1.96 us: 1.06x faster                                                       |
| bench_mp_pool              | 67.2 ms                                                     | 63.4 ms: 1.06x faster                                                       |
| sympy_sum                  | 90.1 ms                                                     | 85.5 ms: 1.05x faster                                                       |
| pickle                     | 7.38 us                                                     | 7.01 us: 1.05x faster                                                       |
| deepcopy                   | 233 us                                                      | 224 us: 1.04x faster                                                        |
| unpickle_list              | 2.69 us                                                     | 2.60 us: 1.04x faster                                                       |
| pickle_dict                | 18.9 us                                                     | 18.3 us: 1.03x faster                                                       |
| logging_silent             | 60.5 ns                                                     | 58.8 ns: 1.03x faster                                                       |
| coroutines                 | 14.1 ms                                                     | 13.8 ms: 1.03x faster                                                       |
| sympy_str                  | 171 ms                                                      | 167 ms: 1.02x faster                                                        |
| async_tree_none            | 286 ms                                                      | 279 ms: 1.02x faster                                                        |
| sqlglot_normalize          | 183 ms                                                      | 180 ms: 1.02x faster                                                        |
| unpickle                   | 8.44 us                                                     | 8.27 us: 1.02x faster                                                       |
| async_tree_cpu_io_mixed    | 477 ms                                                      | 468 ms: 1.02x faster                                                        |
| pidigits                   | 150 ms                                                      | 147 ms: 1.02x faster                                                        |
| json_loads                 | 13.6 us                                                     | 13.4 us: 1.02x faster                                                       |
| json_dumps                 | 5.83 ms                                                     | 5.73 ms: 1.02x faster                                                       |
| regex_effbot               | 1.58 ms                                                     | 1.56 ms: 1.02x faster                                                       |
| xml_etree_process          | 37.6 ms                                                     | 37.1 ms: 1.01x faster                                                       |
| pathlib                    | 79.6 ms                                                     | 78.5 ms: 1.01x faster                                                       |
| xml_etree_generate         | 55.8 ms                                                     | 55.0 ms: 1.01x faster                                                       |
| pickle_list                | 2.88 us                                                     | 2.85 us: 1.01x faster                                                       |
| regex_dna                  | 119 ms                                                      | 118 ms: 1.01x faster                                                        |
| sqlglot_optimize           | 34.0 ms                                                     | 33.7 ms: 1.01x faster                                                       |
| dulwich_log                | 42.7 ms                                                     | 42.5 ms: 1.01x faster                                                       |
| gc_traversal               | 1.49 ms                                                     | 1.50 ms: 1.01x slower                                                       |
| async_tree_cpu_io_mixed_tg | 483 ms                                                      | 492 ms: 1.02x slower                                                        |
| spectral_norm              | 63.9 ms                                                     | 65.1 ms: 1.02x slower                                                       |
| mdp                        | 1.42 sec                                                    | 1.45 sec: 1.02x slower                                                      |
| sympy_expand               | 278 ms                                                      | 285 ms: 1.02x slower                                                        |
| xml_etree_parse            | 90.5 ms                                                     | 92.8 ms: 1.03x slower                                                       |
| chameleon                  | 4.95 ms                                                     | 5.09 ms: 1.03x slower                                                       |
| richards_super             | 31.2 ms                                                     | 32.1 ms: 1.03x slower                                                       |
| tornado_http               | 87.2 ms                                                     | 89.8 ms: 1.03x slower                                                       |
| async_generators           | 230 ms                                                      | 237 ms: 1.03x slower                                                        |
| async_tree_io              | 712 ms                                                      | 734 ms: 1.03x slower                                                        |
| scimark_sor                | 79.8 ms                                                     | 82.3 ms: 1.03x slower                                                       |
| bench_thread_pool          | 830 us                                                      | 857 us: 1.03x slower                                                        |
| richards                   | 27.6 ms                                                     | 28.8 ms: 1.04x slower                                                       |
| sympy_integrate            | 13.0 ms                                                     | 13.5 ms: 1.04x slower                                                       |
| python_startup             | 18.8 ms                                                     | 19.7 ms: 1.04x slower                                                       |
| scimark_lu                 | 57.5 ms                                                     | 60.1 ms: 1.05x slower                                                       |
| 2to3                       | 213 ms                                                      | 223 ms: 1.05x slower                                                        |
| async_tree_io_tg           | 742 ms                                                      | 783 ms: 1.05x slower                                                        |
| logging_format             | 6.72 us                                                     | 7.09 us: 1.06x slower                                                       |
| async_tree_none_tg         | 277 ms                                                      | 293 ms: 1.06x slower                                                        |
| async_tree_memoization     | 333 ms                                                      | 354 ms: 1.06x slower                                                        |
| deepcopy_memo              | 23.4 us                                                     | 25.0 us: 1.07x slower                                                       |
| logging_simple             | 6.21 us                                                     | 6.70 us: 1.08x slower                                                       |
| pycparser                  | 673 ms                                                      | 731 ms: 1.09x slower                                                        |
| xml_etree_iterparse        | 63.1 ms                                                     | 68.7 ms: 1.09x slower                                                       |
| async_tree_memoization_tg  | 345 ms                                                      | 375 ms: 1.09x slower                                                        |
| chaos                      | 42.1 ms                                                     | 45.9 ms: 1.09x slower                                                       |
| regex_compile              | 87.2 ms                                                     | 95.5 ms: 1.09x slower                                                       |
| unpickle_pure_python       | 134 us                                                      | 147 us: 1.10x slower                                                        |
| unpack_sequence            | 36.9 ns                                                     | 40.5 ns: 1.10x slower                                                       |
| pprint_safe_repr           | 508 ms                                                      | 562 ms: 1.11x slower                                                        |
| pprint_pformat             | 1.04 sec                                                    | 1.15 sec: 1.11x slower                                                      |
| regex_v8                   | 13.5 ms                                                     | 15.0 ms: 1.11x slower                                                       |
| meteor_contest             | 72.1 ms                                                     | 80.3 ms: 1.11x slower                                                       |
| go                         | 89.0 ms                                                     | 101 ms: 1.13x slower                                                        |
| python_startup_no_site     | 15.9 ms                                                     | 18.1 ms: 1.14x slower                                                       |
| crypto_pyaes               | 46.4 ms                                                     | 52.9 ms: 1.14x slower                                                       |
| coverage                   | 39.8 ms                                                     | 45.4 ms: 1.14x slower                                                       |
| scimark_monte_carlo        | 43.0 ms                                                     | 49.2 ms: 1.14x slower                                                       |
| telco                      | 4.08 ms                                                     | 4.74 ms: 1.16x slower                                                       |
| comprehensions             | 14.0 us                                                     | 16.5 us: 1.18x slower                                                       |
| pyflate                    | 294 ms                                                      | 347 ms: 1.18x slower                                                        |
| nqueens                    | 61.7 ms                                                     | 74.2 ms: 1.20x slower                                                       |
| float                      | 54.7 ms                                                     | 66.0 ms: 1.21x slower                                                       |
| scimark_fft                | 181 ms                                                      | 220 ms: 1.21x slower                                                        |
| mako                       | 7.05 ms                                                     | 8.56 ms: 1.21x slower                                                       |
| nbody                      | 68.8 ms                                                     | 86.6 ms: 1.26x slower                                                       |
| tomli_loads                | 1.38 sec                                                    | 1.75 sec: 1.27x slower                                                      |
| fannkuch                   | 244 ms                                                      | 313 ms: 1.28x slower                                                        |
| mypy2                      | 209 ms                                                      | 293 ms: 1.40x slower                                                        |
| scimark_sparse_mat_mult    | 2.51 ms                                                     | 3.63 ms: 1.45x slower                                                       |
| deltablue                  | 2.12 ms                                                     | 3.15 ms: 1.48x slower                                                       |
| hexiom                     | 4.00 ms                                                     | 6.30 ms: 1.58x slower                                                       |
| Geometric mean             | (ref)                                                       | 1.06x slower                                                                |

Benchmark hidden because not significant (7): asyncio_tcp_ssl, create_gc_cycles, docutils, sqlglot_parse, sqlglot_transpile, asyncio_tcp, json
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
