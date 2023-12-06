
# Results vs. 3.12.0

- fork: python
- ref: 1a969b4f55f92a17bec8
- machine: windows-amd64
- commit hash: 1a969b4
- commit date: 2023-11-19
- overall geometric mean: 1.01x faster \*
- HPT reliability: 99.46%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 209 ms: 1.02x faster                                                        |
| chameleon      | 4.95 ms                                                     | 4.92 ms: 1.01x faster                                                       |
| docutils       | 1.61 sec                                                    | 1.54 sec: 1.05x faster                                                      |
| tornado_http   | 87.2 ms                                                     | 86.1 ms: 1.01x faster                                                       |
| Geometric mean | (ref)                                                       | 1.02x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|---------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none           | 286 ms                                                      | 265 ms: 1.08x faster                                                        |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 451 ms: 1.06x faster                                                        |
| async_tree_io             | 712 ms                                                      | 724 ms: 1.02x slower                                                        |
| async_tree_memoization    | 333 ms                                                      | 339 ms: 1.02x slower                                                        |
| async_tree_io_tg          | 742 ms                                                      | 759 ms: 1.02x slower                                                        |
| async_tree_none_tg        | 277 ms                                                      | 283 ms: 1.02x slower                                                        |
| async_tree_memoization_tg | 345 ms                                                      | 362 ms: 1.05x slower                                                        |
| Geometric mean            | (ref)                                                       | 1.00x faster                                                                |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 54.7 ms                                                     | 53.1 ms: 1.03x faster                                                       |
| pidigits       | 150 ms                                                      | 147 ms: 1.02x faster                                                        |
| nbody          | 68.8 ms                                                     | 84.3 ms: 1.23x slower                                                       |
| Geometric mean | (ref)                                                       | 1.05x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 87.2 ms                                                     | 80.2 ms: 1.09x faster                                                       |
| regex_dna      | 119 ms                                                      | 121 ms: 1.02x slower                                                        |
| regex_v8       | 13.5 ms                                                     | 16.2 ms: 1.20x slower                                                       |
| Geometric mean | (ref)                                                       | 1.03x slower                                                                |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_pure_python   | 195 us                                                      | 185 us: 1.05x faster                                                        |
| pickle               | 7.38 us                                                     | 7.12 us: 1.04x faster                                                       |
| pickle_dict          | 18.9 us                                                     | 18.3 us: 1.03x faster                                                       |
| json_dumps           | 5.83 ms                                                     | 5.64 ms: 1.03x faster                                                       |
| unpickle             | 8.44 us                                                     | 8.21 us: 1.03x faster                                                       |
| xml_etree_generate   | 55.8 ms                                                     | 54.5 ms: 1.02x faster                                                       |
| xml_etree_process    | 37.6 ms                                                     | 36.8 ms: 1.02x faster                                                       |
| unpickle_pure_python | 134 us                                                      | 132 us: 1.01x faster                                                        |
| json_loads           | 13.6 us                                                     | 13.4 us: 1.01x faster                                                       |
| xml_etree_iterparse  | 63.1 ms                                                     | 63.8 ms: 1.01x slower                                                       |
| unpickle_list        | 2.69 us                                                     | 2.74 us: 1.02x slower                                                       |
| xml_etree_parse      | 90.5 ms                                                     | 92.6 ms: 1.02x slower                                                       |
| tomli_loads          | 1.38 sec                                                    | 1.43 sec: 1.04x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (1): pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 19.8 ms: 1.05x slower                                                       |
| python_startup_no_site | 15.9 ms                                                     | 17.5 ms: 1.10x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.08x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 6.45 ms: 1.09x faster                                                       |

All benchmarks:
===============

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|---------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| comprehensions            | 14.0 us                                                     | 10.6 us: 1.32x faster                                                       |
| typing_runtime_protocols  | 96.7 us                                                     | 74.3 us: 1.30x faster                                                       |
| raytrace                  | 192 ms                                                      | 168 ms: 1.14x faster                                                        |
| sqlite_synth              | 1.75 us                                                     | 1.56 us: 1.12x faster                                                       |
| mako                      | 7.05 ms                                                     | 6.45 ms: 1.09x faster                                                       |
| sympy_sum                 | 90.1 ms                                                     | 82.8 ms: 1.09x faster                                                       |
| regex_compile             | 87.2 ms                                                     | 80.2 ms: 1.09x faster                                                       |
| sympy_str                 | 171 ms                                                      | 158 ms: 1.08x faster                                                        |
| async_tree_none           | 286 ms                                                      | 265 ms: 1.08x faster                                                        |
| bench_mp_pool             | 67.2 ms                                                     | 62.9 ms: 1.07x faster                                                       |
| deepcopy                  | 233 us                                                      | 218 us: 1.07x faster                                                        |
| generators                | 22.6 ms                                                     | 21.3 ms: 1.06x faster                                                       |
| pathlib                   | 79.6 ms                                                     | 75.2 ms: 1.06x faster                                                       |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 451 ms: 1.06x faster                                                        |
| pickle_pure_python        | 195 us                                                      | 185 us: 1.05x faster                                                        |
| mdp                       | 1.42 sec                                                    | 1.35 sec: 1.05x faster                                                      |
| deepcopy_reduce           | 2.08 us                                                     | 1.98 us: 1.05x faster                                                       |
| sympy_integrate           | 13.0 ms                                                     | 12.3 ms: 1.05x faster                                                       |
| docutils                  | 1.61 sec                                                    | 1.54 sec: 1.05x faster                                                      |
| dulwich_log               | 42.7 ms                                                     | 40.8 ms: 1.05x faster                                                       |
| nqueens                   | 61.7 ms                                                     | 59.0 ms: 1.05x faster                                                       |
| crypto_pyaes              | 46.4 ms                                                     | 44.4 ms: 1.05x faster                                                       |
| sqlglot_parse             | 802 us                                                      | 767 us: 1.05x faster                                                        |
| sqlglot_normalize         | 183 ms                                                      | 176 ms: 1.04x faster                                                        |
| pickle                    | 7.38 us                                                     | 7.12 us: 1.04x faster                                                       |
| logging_silent            | 60.5 ns                                                     | 58.5 ns: 1.03x faster                                                       |
| pickle_dict               | 18.9 us                                                     | 18.3 us: 1.03x faster                                                       |
| json_dumps                | 5.83 ms                                                     | 5.64 ms: 1.03x faster                                                       |
| scimark_sparse_mat_mult   | 2.51 ms                                                     | 2.44 ms: 1.03x faster                                                       |
| float                     | 54.7 ms                                                     | 53.1 ms: 1.03x faster                                                       |
| sqlglot_transpile         | 1.02 ms                                                     | 988 us: 1.03x faster                                                        |
| unpickle                  | 8.44 us                                                     | 8.21 us: 1.03x faster                                                       |
| async_generators          | 230 ms                                                      | 224 ms: 1.03x faster                                                        |
| chaos                     | 42.1 ms                                                     | 41.1 ms: 1.03x faster                                                       |
| sympy_expand              | 278 ms                                                      | 271 ms: 1.02x faster                                                        |
| scimark_fft               | 181 ms                                                      | 177 ms: 1.02x faster                                                        |
| xml_etree_generate        | 55.8 ms                                                     | 54.5 ms: 1.02x faster                                                       |
| xml_etree_process         | 37.6 ms                                                     | 36.8 ms: 1.02x faster                                                       |
| pidigits                  | 150 ms                                                      | 147 ms: 1.02x faster                                                        |
| 2to3                      | 213 ms                                                      | 209 ms: 1.02x faster                                                        |
| deltablue                 | 2.12 ms                                                     | 2.09 ms: 1.02x faster                                                       |
| sqlglot_optimize          | 34.0 ms                                                     | 33.5 ms: 1.02x faster                                                       |
| scimark_monte_carlo       | 43.0 ms                                                     | 42.3 ms: 1.02x faster                                                       |
| unpickle_pure_python      | 134 us                                                      | 132 us: 1.01x faster                                                        |
| json_loads                | 13.6 us                                                     | 13.4 us: 1.01x faster                                                       |
| hexiom                    | 4.00 ms                                                     | 3.94 ms: 1.01x faster                                                       |
| tornado_http              | 87.2 ms                                                     | 86.1 ms: 1.01x faster                                                       |
| go                        | 89.0 ms                                                     | 88.0 ms: 1.01x faster                                                       |
| logging_format            | 6.72 us                                                     | 6.64 us: 1.01x faster                                                       |
| pprint_pformat            | 1.04 sec                                                    | 1.03 sec: 1.01x faster                                                      |
| gc_traversal              | 1.49 ms                                                     | 1.48 ms: 1.01x faster                                                       |
| chameleon                 | 4.95 ms                                                     | 4.92 ms: 1.01x faster                                                       |
| pprint_safe_repr          | 508 ms                                                      | 506 ms: 1.00x faster                                                        |
| xml_etree_iterparse       | 63.1 ms                                                     | 63.8 ms: 1.01x slower                                                       |
| scimark_lu                | 57.5 ms                                                     | 58.3 ms: 1.01x slower                                                       |
| unpickle_list             | 2.69 us                                                     | 2.74 us: 1.02x slower                                                       |
| regex_dna                 | 119 ms                                                      | 121 ms: 1.02x slower                                                        |
| async_tree_io             | 712 ms                                                      | 724 ms: 1.02x slower                                                        |
| unpack_sequence           | 36.9 ns                                                     | 37.6 ns: 1.02x slower                                                       |
| meteor_contest            | 72.1 ms                                                     | 73.5 ms: 1.02x slower                                                       |
| async_tree_memoization    | 333 ms                                                      | 339 ms: 1.02x slower                                                        |
| deepcopy_memo             | 23.4 us                                                     | 23.9 us: 1.02x slower                                                       |
| xml_etree_parse           | 90.5 ms                                                     | 92.6 ms: 1.02x slower                                                       |
| async_tree_io_tg          | 742 ms                                                      | 759 ms: 1.02x slower                                                        |
| async_tree_none_tg        | 277 ms                                                      | 283 ms: 1.02x slower                                                        |
| scimark_sor               | 79.8 ms                                                     | 82.2 ms: 1.03x slower                                                       |
| tomli_loads               | 1.38 sec                                                    | 1.43 sec: 1.04x slower                                                      |
| richards                  | 27.6 ms                                                     | 28.8 ms: 1.04x slower                                                       |
| async_tree_memoization_tg | 345 ms                                                      | 362 ms: 1.05x slower                                                        |
| fannkuch                  | 244 ms                                                      | 256 ms: 1.05x slower                                                        |
| python_startup            | 18.8 ms                                                     | 19.8 ms: 1.05x slower                                                       |
| python_startup_no_site    | 15.9 ms                                                     | 17.5 ms: 1.10x slower                                                       |
| coverage                  | 39.8 ms                                                     | 43.9 ms: 1.10x slower                                                       |
| telco                     | 4.08 ms                                                     | 4.64 ms: 1.14x slower                                                       |
| pycparser                 | 673 ms                                                      | 773 ms: 1.15x slower                                                        |
| regex_v8                  | 13.5 ms                                                     | 16.2 ms: 1.20x slower                                                       |
| nbody                     | 68.8 ms                                                     | 84.3 ms: 1.23x slower                                                       |
| mypy2                     | 209 ms                                                      | 286 ms: 1.37x slower                                                        |
| Geometric mean            | (ref)                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (14): asyncio_tcp, dask, logging_simple, coroutines, async_tree_cpu_io_mixed_tg, richards_super, regex_effbot, spectral_norm, pyflate, asyncio_tcp_ssl, pickle_list, bench_thread_pool, create_gc_cycles, json
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.46% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
