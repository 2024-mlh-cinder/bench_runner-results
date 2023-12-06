
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: windows-amd64
- commit hash: 9c583f3
- commit date: 2023-11-04
- overall geometric mean: 1.01x faster \*
- HPT reliability: 92.96%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-pythonperf1-amd64-python-3.12-3.12.0+-9c583f3 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| chameleon      | 4.95 ms                                                     | 5.01 ms: 1.01x slower                                     |
| docutils       | 1.61 sec                                                    | 1.58 sec: 1.02x faster                                    |
| Geometric mean | (ref)                                                       | 1.00x faster                                              |

Benchmark hidden because not significant (2): 2to3, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark          | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-pythonperf1-amd64-python-3.12-3.12.0+-9c583f3 |
|--------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| async_tree_none_tg | 277 ms                                                      | 280 ms: 1.01x slower                                      |
| async_tree_io      | 712 ms                                                      | 724 ms: 1.02x slower                                      |
| Geometric mean     | (ref)                                                       | 1.01x slower                                              |

Benchmark hidden because not significant (6): async_tree_cpu_io_mixed, async_tree_io_tg, async_tree_cpu_io_mixed_tg, async_tree_none, async_tree_memoization, async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-pythonperf1-amd64-python-3.12-3.12.0+-9c583f3 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| nbody          | 68.8 ms                                                     | 67.6 ms: 1.02x faster                                     |
| float          | 54.7 ms                                                     | 53.9 ms: 1.01x faster                                     |
| pidigits       | 150 ms                                                      | 152 ms: 1.01x slower                                      |
| Geometric mean | (ref)                                                       | 1.01x faster                                              |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-pythonperf1-amd64-python-3.12-3.12.0+-9c583f3 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| regex_compile  | 87.2 ms                                                     | 85.8 ms: 1.02x faster                                     |
| regex_dna      | 119 ms                                                      | 120 ms: 1.00x slower                                      |
| regex_effbot   | 1.58 ms                                                     | 1.59 ms: 1.00x slower                                     |
| regex_v8       | 13.5 ms                                                     | 13.8 ms: 1.02x slower                                     |
| Geometric mean | (ref)                                                       | 1.00x slower                                              |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-pythonperf1-amd64-python-3.12-3.12.0+-9c583f3 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| pickle               | 7.38 us                                                     | 7.07 us: 1.04x faster                                     |
| json_dumps           | 5.83 ms                                                     | 5.60 ms: 1.04x faster                                     |
| unpickle             | 8.44 us                                                     | 8.12 us: 1.04x faster                                     |
| pickle_dict          | 18.9 us                                                     | 18.3 us: 1.04x faster                                     |
| unpickle_pure_python | 134 us                                                      | 132 us: 1.02x faster                                      |
| json_loads           | 13.6 us                                                     | 13.4 us: 1.02x faster                                     |
| pickle_pure_python   | 195 us                                                      | 192 us: 1.01x faster                                      |
| xml_etree_generate   | 55.8 ms                                                     | 55.4 ms: 1.01x faster                                     |
| pickle_list          | 2.88 us                                                     | 2.90 us: 1.01x slower                                     |
| unpickle_list        | 2.69 us                                                     | 2.80 us: 1.04x slower                                     |
| Geometric mean       | (ref)                                                       | 1.01x faster                                              |

Benchmark hidden because not significant (4): xml_etree_iterparse, xml_etree_process, xml_etree_parse, tomli_loads

Benchmarks with tag 'startup':
==============================

Benchmark hidden because not significant (2): python_startup_no_site, python_startup

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-pythonperf1-amd64-python-3.12-3.12.0+-9c583f3 |
|-----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| mako            | 7.05 ms                                                     | 6.89 ms: 1.02x faster                                     |
| django_template | 22.8 ms                                                     | 23.3 ms: 1.02x slower                                     |
| Geometric mean  | (ref)                                                       | 1.00x faster                                              |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-pythonperf1-amd64-python-3.12-3.12.0+-9c583f3 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| typing_runtime_protocols | 96.7 us                                                     | 77.7 us: 1.24x faster                                     |
| bench_mp_pool            | 67.2 ms                                                     | 63.1 ms: 1.07x faster                                     |
| pickle                   | 7.38 us                                                     | 7.07 us: 1.04x faster                                     |
| json_dumps               | 5.83 ms                                                     | 5.60 ms: 1.04x faster                                     |
| unpickle                 | 8.44 us                                                     | 8.12 us: 1.04x faster                                     |
| pickle_dict              | 18.9 us                                                     | 18.3 us: 1.04x faster                                     |
| richards                 | 27.6 ms                                                     | 26.6 ms: 1.04x faster                                     |
| richards_super           | 31.2 ms                                                     | 30.1 ms: 1.04x faster                                     |
| scimark_sor              | 79.8 ms                                                     | 77.2 ms: 1.03x faster                                     |
| go                       | 89.0 ms                                                     | 86.3 ms: 1.03x faster                                     |
| sympy_sum                | 90.1 ms                                                     | 87.7 ms: 1.03x faster                                     |
| mako                     | 7.05 ms                                                     | 6.89 ms: 1.02x faster                                     |
| sympy_integrate          | 13.0 ms                                                     | 12.7 ms: 1.02x faster                                     |
| unpack_sequence          | 36.9 ns                                                     | 36.1 ns: 1.02x faster                                     |
| fannkuch                 | 244 ms                                                      | 239 ms: 1.02x faster                                      |
| generators               | 22.6 ms                                                     | 22.1 ms: 1.02x faster                                     |
| nqueens                  | 61.7 ms                                                     | 60.5 ms: 1.02x faster                                     |
| gc_traversal             | 1.49 ms                                                     | 1.46 ms: 1.02x faster                                     |
| nbody                    | 68.8 ms                                                     | 67.6 ms: 1.02x faster                                     |
| unpickle_pure_python     | 134 us                                                      | 132 us: 1.02x faster                                      |
| scimark_sparse_mat_mult  | 2.51 ms                                                     | 2.47 ms: 1.02x faster                                     |
| regex_compile            | 87.2 ms                                                     | 85.8 ms: 1.02x faster                                     |
| json_loads               | 13.6 us                                                     | 13.4 us: 1.02x faster                                     |
| deepcopy                 | 233 us                                                      | 229 us: 1.02x faster                                      |
| docutils                 | 1.61 sec                                                    | 1.58 sec: 1.02x faster                                    |
| async_generators         | 230 ms                                                      | 227 ms: 1.02x faster                                      |
| float                    | 54.7 ms                                                     | 53.9 ms: 1.01x faster                                     |
| pickle_pure_python       | 195 us                                                      | 192 us: 1.01x faster                                      |
| json                     | 2.94 ms                                                     | 2.90 ms: 1.01x faster                                     |
| telco                    | 4.08 ms                                                     | 4.03 ms: 1.01x faster                                     |
| spectral_norm            | 63.9 ms                                                     | 63.1 ms: 1.01x faster                                     |
| dulwich_log              | 42.7 ms                                                     | 42.2 ms: 1.01x faster                                     |
| deepcopy_memo            | 23.4 us                                                     | 23.1 us: 1.01x faster                                     |
| sympy_str                | 171 ms                                                      | 170 ms: 1.01x faster                                      |
| pathlib                  | 79.6 ms                                                     | 78.8 ms: 1.01x faster                                     |
| crypto_pyaes             | 46.4 ms                                                     | 46.0 ms: 1.01x faster                                     |
| coverage                 | 39.8 ms                                                     | 39.4 ms: 1.01x faster                                     |
| pyflate                  | 294 ms                                                      | 291 ms: 1.01x faster                                      |
| deepcopy_reduce          | 2.08 us                                                     | 2.07 us: 1.01x faster                                     |
| sqlite_synth             | 1.75 us                                                     | 1.73 us: 1.01x faster                                     |
| sqlalchemy_imperative    | 9.20 ms                                                     | 9.13 ms: 1.01x faster                                     |
| xml_etree_generate       | 55.8 ms                                                     | 55.4 ms: 1.01x faster                                     |
| pprint_pformat           | 1.04 sec                                                    | 1.03 sec: 1.01x faster                                    |
| pprint_safe_repr         | 508 ms                                                      | 505 ms: 1.00x faster                                      |
| raytrace                 | 192 ms                                                      | 192 ms: 1.00x faster                                      |
| sympy_expand             | 278 ms                                                      | 277 ms: 1.00x faster                                      |
| comprehensions           | 14.0 us                                                     | 13.9 us: 1.00x faster                                     |
| mypy2                    | 209 ms                                                      | 208 ms: 1.00x faster                                      |
| regex_dna                | 119 ms                                                      | 120 ms: 1.00x slower                                      |
| sqlglot_optimize         | 34.0 ms                                                     | 34.1 ms: 1.00x slower                                     |
| regex_effbot             | 1.58 ms                                                     | 1.59 ms: 1.00x slower                                     |
| sqlglot_normalize        | 183 ms                                                      | 184 ms: 1.00x slower                                      |
| logging_silent           | 60.5 ns                                                     | 60.8 ns: 1.01x slower                                     |
| pickle_list              | 2.88 us                                                     | 2.90 us: 1.01x slower                                     |
| chaos                    | 42.1 ms                                                     | 42.4 ms: 1.01x slower                                     |
| scimark_lu               | 57.5 ms                                                     | 58.0 ms: 1.01x slower                                     |
| pidigits                 | 150 ms                                                      | 152 ms: 1.01x slower                                      |
| chameleon                | 4.95 ms                                                     | 5.01 ms: 1.01x slower                                     |
| async_tree_none_tg       | 277 ms                                                      | 280 ms: 1.01x slower                                      |
| hexiom                   | 4.00 ms                                                     | 4.06 ms: 1.02x slower                                     |
| deltablue                | 2.12 ms                                                     | 2.16 ms: 1.02x slower                                     |
| async_tree_io            | 712 ms                                                      | 724 ms: 1.02x slower                                      |
| logging_simple           | 6.21 us                                                     | 6.32 us: 1.02x slower                                     |
| regex_v8                 | 13.5 ms                                                     | 13.8 ms: 1.02x slower                                     |
| django_template          | 22.8 ms                                                     | 23.3 ms: 1.02x slower                                     |
| sqlglot_transpile        | 1.02 ms                                                     | 1.04 ms: 1.02x slower                                     |
| meteor_contest           | 72.1 ms                                                     | 73.9 ms: 1.02x slower                                     |
| sqlglot_parse            | 802 us                                                      | 830 us: 1.04x slower                                      |
| scimark_monte_carlo      | 43.0 ms                                                     | 44.5 ms: 1.04x slower                                     |
| unpickle_list            | 2.69 us                                                     | 2.80 us: 1.04x slower                                     |
| pycparser                | 673 ms                                                      | 710 ms: 1.05x slower                                      |
| mdp                      | 1.42 sec                                                    | 1.51 sec: 1.07x slower                                    |
| Geometric mean           | (ref)                                                       | 1.01x faster                                              |

Benchmark hidden because not significant (24): bench_thread_pool, 2to3, create_gc_cycles, dask, scimark_fft, xml_etree_iterparse, sqlalchemy_declarative, coroutines, async_tree_cpu_io_mixed, async_tree_io_tg, xml_etree_process, xml_etree_parse, tornado_http, python_startup_no_site, tomli_loads, logging_format, async_tree_cpu_io_mixed_tg, python_startup, aiohttp, async_tree_none, async_tree_memoization, async_tree_memoization_tg, asyncio_tcp, asyncio_tcp_ssl


# HPT report

- Reliability score: 92.96% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
