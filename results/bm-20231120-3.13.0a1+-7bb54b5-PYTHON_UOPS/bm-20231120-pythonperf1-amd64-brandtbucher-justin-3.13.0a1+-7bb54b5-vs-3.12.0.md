
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: 7bb54b5
- commit date: 2023-11-20
- overall geometric mean: 1.01x faster \*
- HPT reliability: 88.17%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 218 ms: 1.03x slower                                                |
| chameleon      | 4.95 ms                                                     | 4.89 ms: 1.01x faster                                               |
| docutils       | 1.61 sec                                                    | 1.57 sec: 1.02x faster                                              |
| tornado_http   | 87.2 ms                                                     | 97.5 ms: 1.12x slower                                               |
| Geometric mean | (ref)                                                       | 1.03x slower                                                        |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|---------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| async_tree_none           | 286 ms                                                      | 263 ms: 1.09x faster                                                |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 450 ms: 1.06x faster                                                |
| async_tree_io             | 712 ms                                                      | 721 ms: 1.01x slower                                                |
| async_tree_memoization    | 333 ms                                                      | 338 ms: 1.02x slower                                                |
| async_tree_none_tg        | 277 ms                                                      | 281 ms: 1.02x slower                                                |
| async_tree_io_tg          | 742 ms                                                      | 767 ms: 1.03x slower                                                |
| async_tree_memoization_tg | 345 ms                                                      | 364 ms: 1.06x slower                                                |
| Geometric mean            | (ref)                                                       | 1.00x faster                                                        |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| float          | 54.7 ms                                                     | 51.3 ms: 1.07x faster                                               |
| nbody          | 68.8 ms                                                     | 64.6 ms: 1.07x faster                                               |
| pidigits       | 150 ms                                                      | 150 ms: 1.00x faster                                                |
| Geometric mean | (ref)                                                       | 1.04x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 87.2 ms                                                     | 81.1 ms: 1.08x faster                                               |
| regex_dna      | 119 ms                                                      | 120 ms: 1.01x slower                                                |
| regex_v8       | 13.5 ms                                                     | 17.9 ms: 1.32x slower                                               |
| Geometric mean | (ref)                                                       | 1.06x slower                                                        |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| pickle               | 7.38 us                                                     | 6.86 us: 1.08x faster                                               |
| tomli_loads          | 1.38 sec                                                    | 1.28 sec: 1.08x faster                                              |
| pickle_pure_python   | 195 us                                                      | 184 us: 1.06x faster                                                |
| pickle_dict          | 18.9 us                                                     | 18.1 us: 1.05x faster                                               |
| json_dumps           | 5.83 ms                                                     | 5.64 ms: 1.03x faster                                               |
| unpickle             | 8.44 us                                                     | 8.17 us: 1.03x faster                                               |
| xml_etree_iterparse  | 63.1 ms                                                     | 61.5 ms: 1.03x faster                                               |
| xml_etree_generate   | 55.8 ms                                                     | 54.5 ms: 1.02x faster                                               |
| xml_etree_process    | 37.6 ms                                                     | 36.8 ms: 1.02x faster                                               |
| unpickle_pure_python | 134 us                                                      | 132 us: 1.02x faster                                                |
| unpickle_list        | 2.69 us                                                     | 2.65 us: 1.02x faster                                               |
| json_loads           | 13.6 us                                                     | 13.4 us: 1.01x faster                                               |
| xml_etree_parse      | 90.5 ms                                                     | 91.6 ms: 1.01x slower                                               |
| pickle_list          | 2.88 us                                                     | 3.19 us: 1.11x slower                                               |
| Geometric mean       | (ref)                                                       | 1.02x faster                                                        |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.7 ms: 1.10x slower                                               |
| python_startup_no_site | 15.9 ms                                                     | 18.7 ms: 1.17x slower                                               |
| Geometric mean         | (ref)                                                       | 1.13x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|-----------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 6.19 ms: 1.14x faster                                               |

All benchmarks:
===============

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|---------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols  | 96.7 us                                                     | 74.3 us: 1.30x faster                                               |
| comprehensions            | 14.0 us                                                     | 11.2 us: 1.25x faster                                               |
| mako                      | 7.05 ms                                                     | 6.19 ms: 1.14x faster                                               |
| sqlite_synth              | 1.75 us                                                     | 1.55 us: 1.13x faster                                               |
| raytrace                  | 192 ms                                                      | 173 ms: 1.12x faster                                                |
| asyncio_tcp_ssl           | 1.89 sec                                                    | 1.72 sec: 1.10x faster                                              |
| generators                | 22.6 ms                                                     | 20.6 ms: 1.10x faster                                               |
| spectral_norm             | 63.9 ms                                                     | 58.6 ms: 1.09x faster                                               |
| async_tree_none           | 286 ms                                                      | 263 ms: 1.09x faster                                                |
| pickle                    | 7.38 us                                                     | 6.86 us: 1.08x faster                                               |
| regex_compile             | 87.2 ms                                                     | 81.1 ms: 1.08x faster                                               |
| tomli_loads               | 1.38 sec                                                    | 1.28 sec: 1.08x faster                                              |
| logging_silent            | 60.5 ns                                                     | 56.6 ns: 1.07x faster                                               |
| sympy_str                 | 171 ms                                                      | 161 ms: 1.07x faster                                                |
| float                     | 54.7 ms                                                     | 51.3 ms: 1.07x faster                                               |
| nbody                     | 68.8 ms                                                     | 64.6 ms: 1.07x faster                                               |
| sympy_sum                 | 90.1 ms                                                     | 84.6 ms: 1.06x faster                                               |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 450 ms: 1.06x faster                                                |
| deepcopy_memo             | 23.4 us                                                     | 22.1 us: 1.06x faster                                               |
| pickle_pure_python        | 195 us                                                      | 184 us: 1.06x faster                                                |
| coroutines                | 14.1 ms                                                     | 13.4 ms: 1.06x faster                                               |
| deltablue                 | 2.12 ms                                                     | 2.01 ms: 1.06x faster                                               |
| pickle_dict               | 18.9 us                                                     | 18.1 us: 1.05x faster                                               |
| scimark_sparse_mat_mult   | 2.51 ms                                                     | 2.40 ms: 1.05x faster                                               |
| sqlglot_parse             | 802 us                                                      | 768 us: 1.04x faster                                                |
| deepcopy_reduce           | 2.08 us                                                     | 2.01 us: 1.04x faster                                               |
| deepcopy                  | 233 us                                                      | 224 us: 1.04x faster                                                |
| json_dumps                | 5.83 ms                                                     | 5.64 ms: 1.03x faster                                               |
| unpickle                  | 8.44 us                                                     | 8.17 us: 1.03x faster                                               |
| richards                  | 27.6 ms                                                     | 26.7 ms: 1.03x faster                                               |
| sympy_expand              | 278 ms                                                      | 269 ms: 1.03x faster                                                |
| dulwich_log               | 42.7 ms                                                     | 41.4 ms: 1.03x faster                                               |
| crypto_pyaes              | 46.4 ms                                                     | 45.1 ms: 1.03x faster                                               |
| logging_format            | 6.72 us                                                     | 6.53 us: 1.03x faster                                               |
| richards_super            | 31.2 ms                                                     | 30.4 ms: 1.03x faster                                               |
| mdp                       | 1.42 sec                                                    | 1.38 sec: 1.03x faster                                              |
| xml_etree_iterparse       | 63.1 ms                                                     | 61.5 ms: 1.03x faster                                               |
| xml_etree_generate        | 55.8 ms                                                     | 54.5 ms: 1.02x faster                                               |
| sqlglot_transpile         | 1.02 ms                                                     | 993 us: 1.02x faster                                                |
| docutils                  | 1.61 sec                                                    | 1.57 sec: 1.02x faster                                              |
| xml_etree_process         | 37.6 ms                                                     | 36.8 ms: 1.02x faster                                               |
| pprint_safe_repr          | 508 ms                                                      | 498 ms: 1.02x faster                                                |
| unpickle_pure_python      | 134 us                                                      | 132 us: 1.02x faster                                                |
| bench_mp_pool             | 67.2 ms                                                     | 66.1 ms: 1.02x faster                                               |
| unpickle_list             | 2.69 us                                                     | 2.65 us: 1.02x faster                                               |
| pprint_pformat            | 1.04 sec                                                    | 1.02 sec: 1.02x faster                                              |
| json_loads                | 13.6 us                                                     | 13.4 us: 1.01x faster                                               |
| nqueens                   | 61.7 ms                                                     | 60.9 ms: 1.01x faster                                               |
| logging_simple            | 6.21 us                                                     | 6.12 us: 1.01x faster                                               |
| chameleon                 | 4.95 ms                                                     | 4.89 ms: 1.01x faster                                               |
| fannkuch                  | 244 ms                                                      | 242 ms: 1.01x faster                                                |
| sqlglot_normalize         | 183 ms                                                      | 182 ms: 1.01x faster                                                |
| sympy_integrate           | 13.0 ms                                                     | 12.9 ms: 1.00x faster                                               |
| pidigits                  | 150 ms                                                      | 150 ms: 1.00x faster                                                |
| pyflate                   | 294 ms                                                      | 295 ms: 1.01x slower                                                |
| regex_dna                 | 119 ms                                                      | 120 ms: 1.01x slower                                                |
| xml_etree_parse           | 90.5 ms                                                     | 91.6 ms: 1.01x slower                                               |
| scimark_sor               | 79.8 ms                                                     | 80.7 ms: 1.01x slower                                               |
| pycparser                 | 673 ms                                                      | 682 ms: 1.01x slower                                                |
| async_tree_io             | 712 ms                                                      | 721 ms: 1.01x slower                                                |
| async_tree_memoization    | 333 ms                                                      | 338 ms: 1.02x slower                                                |
| async_tree_none_tg        | 277 ms                                                      | 281 ms: 1.02x slower                                                |
| pathlib                   | 79.6 ms                                                     | 81.0 ms: 1.02x slower                                               |
| sqlglot_optimize          | 34.0 ms                                                     | 34.6 ms: 1.02x slower                                               |
| go                        | 89.0 ms                                                     | 91.3 ms: 1.03x slower                                               |
| async_generators          | 230 ms                                                      | 236 ms: 1.03x slower                                                |
| 2to3                      | 213 ms                                                      | 218 ms: 1.03x slower                                                |
| scimark_lu                | 57.5 ms                                                     | 59.1 ms: 1.03x slower                                               |
| async_tree_io_tg          | 742 ms                                                      | 767 ms: 1.03x slower                                                |
| scimark_fft               | 181 ms                                                      | 188 ms: 1.04x slower                                                |
| meteor_contest            | 72.1 ms                                                     | 75.4 ms: 1.05x slower                                               |
| hexiom                    | 4.00 ms                                                     | 4.18 ms: 1.05x slower                                               |
| bench_thread_pool         | 830 us                                                      | 869 us: 1.05x slower                                                |
| scimark_monte_carlo       | 43.0 ms                                                     | 45.4 ms: 1.06x slower                                               |
| async_tree_memoization_tg | 345 ms                                                      | 364 ms: 1.06x slower                                                |
| dask                      | 255 ms                                                      | 275 ms: 1.08x slower                                                |
| python_startup            | 18.8 ms                                                     | 20.7 ms: 1.10x slower                                               |
| pickle_list               | 2.88 us                                                     | 3.19 us: 1.11x slower                                               |
| asyncio_tcp               | 471 ms                                                      | 524 ms: 1.11x slower                                                |
| tornado_http              | 87.2 ms                                                     | 97.5 ms: 1.12x slower                                               |
| telco                     | 4.08 ms                                                     | 4.64 ms: 1.14x slower                                               |
| coverage                  | 39.8 ms                                                     | 45.9 ms: 1.15x slower                                               |
| python_startup_no_site    | 15.9 ms                                                     | 18.7 ms: 1.17x slower                                               |
| unpack_sequence           | 36.9 ns                                                     | 43.5 ns: 1.18x slower                                               |
| regex_v8                  | 13.5 ms                                                     | 17.9 ms: 1.32x slower                                               |
| mypy2                     | 209 ms                                                      | 294 ms: 1.41x slower                                                |
| Geometric mean            | (ref)                                                       | 1.01x faster                                                        |

Benchmark hidden because not significant (6): async_tree_cpu_io_mixed_tg, chaos, gc_traversal, regex_effbot, create_gc_cycles, json
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 88.17% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
