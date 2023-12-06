
# Results vs. 3.12.0

- fork: python
- ref: 8deb8bc2e5af0e229df8
- machine: windows-amd64
- commit hash: 8deb8bc
- commit date: 2023-11-20
- overall geometric mean: 1.02x faster \*
- HPT reliability: 98.42%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| chameleon      | 4.95 ms                                                     | 4.75 ms: 1.04x faster                                                       |
| docutils       | 1.61 sec                                                    | 1.55 sec: 1.04x faster                                                      |
| tornado_http   | 87.2 ms                                                     | 95.6 ms: 1.10x slower                                                       |
| Geometric mean | (ref)                                                       | 1.00x slower                                                                |

Benchmark hidden because not significant (1): 2to3

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|---------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none           | 286 ms                                                      | 264 ms: 1.08x faster                                                        |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 451 ms: 1.06x faster                                                        |
| async_tree_none_tg        | 277 ms                                                      | 281 ms: 1.01x slower                                                        |
| async_tree_io             | 712 ms                                                      | 722 ms: 1.01x slower                                                        |
| async_tree_memoization    | 333 ms                                                      | 341 ms: 1.03x slower                                                        |
| async_tree_io_tg          | 742 ms                                                      | 762 ms: 1.03x slower                                                        |
| async_tree_memoization_tg | 345 ms                                                      | 364 ms: 1.06x slower                                                        |
| Geometric mean            | (ref)                                                       | 1.00x faster                                                                |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 54.7 ms                                                     | 51.5 ms: 1.06x faster                                                       |
| pidigits       | 150 ms                                                      | 146 ms: 1.02x faster                                                        |
| nbody          | 68.8 ms                                                     | 71.3 ms: 1.04x slower                                                       |
| Geometric mean | (ref)                                                       | 1.02x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 87.2 ms                                                     | 78.7 ms: 1.11x faster                                                       |
| regex_dna      | 119 ms                                                      | 117 ms: 1.02x faster                                                        |
| regex_effbot   | 1.58 ms                                                     | 1.55 ms: 1.02x faster                                                       |
| regex_v8       | 13.5 ms                                                     | 14.6 ms: 1.08x slower                                                       |
| Geometric mean | (ref)                                                       | 1.02x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_pure_python   | 195 us                                                      | 177 us: 1.10x faster                                                        |
| unpickle_pure_python | 134 us                                                      | 127 us: 1.06x faster                                                        |
| json_dumps           | 5.83 ms                                                     | 5.59 ms: 1.04x faster                                                       |
| unpickle             | 8.44 us                                                     | 8.12 us: 1.04x faster                                                       |
| pickle               | 7.38 us                                                     | 7.18 us: 1.03x faster                                                       |
| json_loads           | 13.6 us                                                     | 13.3 us: 1.02x faster                                                       |
| xml_etree_generate   | 55.8 ms                                                     | 54.7 ms: 1.02x faster                                                       |
| pickle_list          | 2.88 us                                                     | 2.85 us: 1.01x faster                                                       |
| xml_etree_process    | 37.6 ms                                                     | 37.4 ms: 1.01x faster                                                       |
| xml_etree_iterparse  | 63.1 ms                                                     | 63.8 ms: 1.01x slower                                                       |
| xml_etree_parse      | 90.5 ms                                                     | 92.6 ms: 1.02x slower                                                       |
| tomli_loads          | 1.38 sec                                                    | 1.42 sec: 1.03x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.02x faster                                                                |

Benchmark hidden because not significant (2): pickle_dict, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.3 ms: 1.08x slower                                                       |
| python_startup_no_site | 15.9 ms                                                     | 18.2 ms: 1.14x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.11x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 6.45 ms: 1.09x faster                                                       |

All benchmarks:
===============

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|---------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| comprehensions            | 14.0 us                                                     | 10.5 us: 1.33x faster                                                       |
| typing_runtime_protocols  | 96.7 us                                                     | 76.2 us: 1.27x faster                                                       |
| raytrace                  | 192 ms                                                      | 166 ms: 1.16x faster                                                        |
| sqlite_synth              | 1.75 us                                                     | 1.56 us: 1.12x faster                                                       |
| regex_compile             | 87.2 ms                                                     | 78.7 ms: 1.11x faster                                                       |
| sympy_sum                 | 90.1 ms                                                     | 82.0 ms: 1.10x faster                                                       |
| pickle_pure_python        | 195 us                                                      | 177 us: 1.10x faster                                                        |
| sympy_str                 | 171 ms                                                      | 157 ms: 1.09x faster                                                        |
| mako                      | 7.05 ms                                                     | 6.45 ms: 1.09x faster                                                       |
| async_tree_none           | 286 ms                                                      | 264 ms: 1.08x faster                                                        |
| logging_silent            | 60.5 ns                                                     | 56.2 ns: 1.08x faster                                                       |
| crypto_pyaes              | 46.4 ms                                                     | 43.2 ms: 1.07x faster                                                       |
| coroutines                | 14.1 ms                                                     | 13.1 ms: 1.07x faster                                                       |
| chaos                     | 42.1 ms                                                     | 39.3 ms: 1.07x faster                                                       |
| hexiom                    | 4.00 ms                                                     | 3.74 ms: 1.07x faster                                                       |
| deepcopy_reduce           | 2.08 us                                                     | 1.96 us: 1.07x faster                                                       |
| float                     | 54.7 ms                                                     | 51.5 ms: 1.06x faster                                                       |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 451 ms: 1.06x faster                                                        |
| unpickle_pure_python      | 134 us                                                      | 127 us: 1.06x faster                                                        |
| sympy_integrate           | 13.0 ms                                                     | 12.3 ms: 1.06x faster                                                       |
| sqlglot_parse             | 802 us                                                      | 762 us: 1.05x faster                                                        |
| deepcopy                  | 233 us                                                      | 222 us: 1.05x faster                                                        |
| bench_mp_pool             | 67.2 ms                                                     | 64.3 ms: 1.05x faster                                                       |
| scimark_monte_carlo       | 43.0 ms                                                     | 41.2 ms: 1.04x faster                                                       |
| json_dumps                | 5.83 ms                                                     | 5.59 ms: 1.04x faster                                                       |
| nqueens                   | 61.7 ms                                                     | 59.1 ms: 1.04x faster                                                       |
| scimark_fft               | 181 ms                                                      | 174 ms: 1.04x faster                                                        |
| sqlglot_transpile         | 1.02 ms                                                     | 976 us: 1.04x faster                                                        |
| chameleon                 | 4.95 ms                                                     | 4.75 ms: 1.04x faster                                                       |
| deltablue                 | 2.12 ms                                                     | 2.04 ms: 1.04x faster                                                       |
| dulwich_log               | 42.7 ms                                                     | 41.1 ms: 1.04x faster                                                       |
| sqlglot_normalize         | 183 ms                                                      | 176 ms: 1.04x faster                                                        |
| docutils                  | 1.61 sec                                                    | 1.55 sec: 1.04x faster                                                      |
| unpickle                  | 8.44 us                                                     | 8.12 us: 1.04x faster                                                       |
| scimark_sor               | 79.8 ms                                                     | 76.8 ms: 1.04x faster                                                       |
| scimark_sparse_mat_mult   | 2.51 ms                                                     | 2.42 ms: 1.04x faster                                                       |
| sympy_expand              | 278 ms                                                      | 268 ms: 1.04x faster                                                        |
| json                      | 2.94 ms                                                     | 2.85 ms: 1.03x faster                                                       |
| logging_format            | 6.72 us                                                     | 6.51 us: 1.03x faster                                                       |
| mdp                       | 1.42 sec                                                    | 1.38 sec: 1.03x faster                                                      |
| pprint_safe_repr          | 508 ms                                                      | 493 ms: 1.03x faster                                                        |
| pprint_pformat            | 1.04 sec                                                    | 1.01 sec: 1.03x faster                                                      |
| pickle                    | 7.38 us                                                     | 7.18 us: 1.03x faster                                                       |
| go                        | 89.0 ms                                                     | 86.8 ms: 1.02x faster                                                       |
| pidigits                  | 150 ms                                                      | 146 ms: 1.02x faster                                                        |
| spectral_norm             | 63.9 ms                                                     | 62.4 ms: 1.02x faster                                                       |
| sqlglot_optimize          | 34.0 ms                                                     | 33.2 ms: 1.02x faster                                                       |
| json_loads                | 13.6 us                                                     | 13.3 us: 1.02x faster                                                       |
| pyflate                   | 294 ms                                                      | 287 ms: 1.02x faster                                                        |
| xml_etree_generate        | 55.8 ms                                                     | 54.7 ms: 1.02x faster                                                       |
| regex_dna                 | 119 ms                                                      | 117 ms: 1.02x faster                                                        |
| regex_effbot              | 1.58 ms                                                     | 1.55 ms: 1.02x faster                                                       |
| logging_simple            | 6.21 us                                                     | 6.12 us: 1.01x faster                                                       |
| generators                | 22.6 ms                                                     | 22.3 ms: 1.01x faster                                                       |
| pickle_list               | 2.88 us                                                     | 2.85 us: 1.01x faster                                                       |
| scimark_lu                | 57.5 ms                                                     | 56.8 ms: 1.01x faster                                                       |
| richards_super            | 31.2 ms                                                     | 31.0 ms: 1.01x faster                                                       |
| xml_etree_process         | 37.6 ms                                                     | 37.4 ms: 1.01x faster                                                       |
| gc_traversal              | 1.49 ms                                                     | 1.50 ms: 1.01x slower                                                       |
| pathlib                   | 79.6 ms                                                     | 80.2 ms: 1.01x slower                                                       |
| xml_etree_iterparse       | 63.1 ms                                                     | 63.8 ms: 1.01x slower                                                       |
| meteor_contest            | 72.1 ms                                                     | 72.9 ms: 1.01x slower                                                       |
| async_generators          | 230 ms                                                      | 233 ms: 1.01x slower                                                        |
| async_tree_none_tg        | 277 ms                                                      | 281 ms: 1.01x slower                                                        |
| async_tree_io             | 712 ms                                                      | 722 ms: 1.01x slower                                                        |
| xml_etree_parse           | 90.5 ms                                                     | 92.6 ms: 1.02x slower                                                       |
| bench_thread_pool         | 830 us                                                      | 849 us: 1.02x slower                                                        |
| async_tree_memoization    | 333 ms                                                      | 341 ms: 1.03x slower                                                        |
| async_tree_io_tg          | 742 ms                                                      | 762 ms: 1.03x slower                                                        |
| tomli_loads               | 1.38 sec                                                    | 1.42 sec: 1.03x slower                                                      |
| richards                  | 27.6 ms                                                     | 28.5 ms: 1.03x slower                                                       |
| fannkuch                  | 244 ms                                                      | 252 ms: 1.03x slower                                                        |
| nbody                     | 68.8 ms                                                     | 71.3 ms: 1.04x slower                                                       |
| unpack_sequence           | 36.9 ns                                                     | 38.5 ns: 1.04x slower                                                       |
| asyncio_tcp_ssl           | 1.89 sec                                                    | 1.99 sec: 1.05x slower                                                      |
| async_tree_memoization_tg | 345 ms                                                      | 364 ms: 1.06x slower                                                        |
| dask                      | 255 ms                                                      | 269 ms: 1.06x slower                                                        |
| python_startup            | 18.8 ms                                                     | 20.3 ms: 1.08x slower                                                       |
| regex_v8                  | 13.5 ms                                                     | 14.6 ms: 1.08x slower                                                       |
| tornado_http              | 87.2 ms                                                     | 95.6 ms: 1.10x slower                                                       |
| telco                     | 4.08 ms                                                     | 4.56 ms: 1.12x slower                                                       |
| asyncio_tcp               | 471 ms                                                      | 531 ms: 1.13x slower                                                        |
| coverage                  | 39.8 ms                                                     | 45.3 ms: 1.14x slower                                                       |
| python_startup_no_site    | 15.9 ms                                                     | 18.2 ms: 1.14x slower                                                       |
| pycparser                 | 673 ms                                                      | 775 ms: 1.15x slower                                                        |
| mypy2                     | 209 ms                                                      | 287 ms: 1.37x slower                                                        |
| Geometric mean            | (ref)                                                       | 1.02x faster                                                                |

Benchmark hidden because not significant (6): async_tree_cpu_io_mixed_tg, 2to3, pickle_dict, deepcopy_memo, unpickle_list, create_gc_cycles
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 98.42% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
