
# Results vs. 3.12.0

- fork: python
- ref: 1a969b4f55f92a17bec8
- machine: linux-x86_64
- commit hash: 1a969b4
- commit date: 2023-11-19
- overall geometric mean: 1.10x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 316 ms: 1.11x slower                                                         |
| chameleon      | 7.27 ms                                                      | 7.93 ms: 1.09x slower                                                        |
| docutils       | 2.89 sec                                                     | 2.93 sec: 1.01x slower                                                       |
| tornado_http   | 122 ms                                                       | 125 ms: 1.02x slower                                                         |
| Geometric mean | (ref)                                                        | 1.06x slower                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none            | 459 ms                                                       | 453 ms: 1.01x faster                                                         |
| async_tree_cpu_io_mixed    | 704 ms                                                       | 718 ms: 1.02x slower                                                         |
| async_tree_memoization     | 554 ms                                                       | 567 ms: 1.02x slower                                                         |
| async_tree_memoization_tg  | 554 ms                                                       | 568 ms: 1.03x slower                                                         |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 732 ms: 1.04x slower                                                         |
| async_tree_none_tg         | 440 ms                                                       | 459 ms: 1.04x slower                                                         |
| async_tree_io_tg           | 1.07 sec                                                     | 1.12 sec: 1.04x slower                                                       |
| async_tree_io              | 1.06 sec                                                     | 1.11 sec: 1.05x slower                                                       |
| Geometric mean             | (ref)                                                        | 1.03x slower                                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| pidigits       | 264 ms                                                       | 267 ms: 1.01x slower                                                         |
| float          | 81.6 ms                                                      | 108 ms: 1.32x slower                                                         |
| nbody          | 88.2 ms                                                      | 120 ms: 1.37x slower                                                         |
| Geometric mean | (ref)                                                        | 1.22x slower                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.52 ms: 1.03x faster                                                        |
| regex_dna      | 240 ms                                                       | 252 ms: 1.05x slower                                                         |
| regex_v8       | 24.4 ms                                                      | 26.2 ms: 1.07x slower                                                        |
| regex_compile  | 145 ms                                                       | 177 ms: 1.23x slower                                                         |
| Geometric mean | (ref)                                                        | 1.08x slower                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 14.5 us: 1.06x faster                                                        |
| pickle_pure_python   | 319 us                                                       | 311 us: 1.03x faster                                                         |
| xml_etree_process    | 58.3 ms                                                      | 57.8 ms: 1.01x faster                                                        |
| pickle               | 10.0 us                                                      | 10.1 us: 1.00x slower                                                        |
| unpickle_list        | 4.65 us                                                      | 4.70 us: 1.01x slower                                                        |
| xml_etree_generate   | 85.3 ms                                                      | 86.8 ms: 1.02x slower                                                        |
| xml_etree_parse      | 147 ms                                                       | 153 ms: 1.04x slower                                                         |
| json_dumps           | 10.3 ms                                                      | 10.7 ms: 1.04x slower                                                        |
| json_loads           | 24.3 us                                                      | 25.5 us: 1.05x slower                                                        |
| pickle_list          | 4.22 us                                                      | 4.49 us: 1.06x slower                                                        |
| xml_etree_iterparse  | 104 ms                                                       | 111 ms: 1.08x slower                                                         |
| unpickle_pure_python | 210 us                                                       | 252 us: 1.20x slower                                                         |
| tomli_loads          | 2.17 sec                                                     | 2.88 sec: 1.33x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.05x slower                                                                 |

Benchmark hidden because not significant (1): pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 12.8 ms: 1.10x slower                                                        |
| python_startup_no_site | 8.67 ms                                                      | 11.3 ms: 1.30x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.19x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 10.1 ms                                                      | 16.9 ms: 1.68x slower                                                        |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| typing_runtime_protocols   | 150 us                                                       | 131 us: 1.14x faster                                                         |
| generators                 | 37.3 ms                                                      | 34.0 ms: 1.10x faster                                                        |
| unpickle                   | 15.3 us                                                      | 14.5 us: 1.06x faster                                                        |
| deepcopy_reduce            | 3.41 us                                                      | 3.26 us: 1.05x faster                                                        |
| coroutines                 | 23.1 ms                                                      | 22.1 ms: 1.04x faster                                                        |
| pickle_pure_python         | 319 us                                                       | 311 us: 1.03x faster                                                         |
| regex_effbot               | 3.61 ms                                                      | 3.52 ms: 1.03x faster                                                        |
| spectral_norm              | 93.9 ms                                                      | 91.7 ms: 1.02x faster                                                        |
| async_generators           | 385 ms                                                       | 379 ms: 1.02x faster                                                         |
| sqlglot_normalize          | 119 ms                                                       | 117 ms: 1.02x faster                                                         |
| sympy_sum                  | 163 ms                                                       | 160 ms: 1.01x faster                                                         |
| async_tree_none            | 459 ms                                                       | 453 ms: 1.01x faster                                                         |
| asyncio_tcp                | 380 ms                                                       | 375 ms: 1.01x faster                                                         |
| deepcopy                   | 371 us                                                       | 367 us: 1.01x faster                                                         |
| xml_etree_process          | 58.3 ms                                                      | 57.8 ms: 1.01x faster                                                        |
| pickle                     | 10.0 us                                                      | 10.1 us: 1.00x slower                                                        |
| asyncio_tcp_ssl            | 1.57 sec                                                     | 1.59 sec: 1.01x slower                                                       |
| pidigits                   | 264 ms                                                       | 267 ms: 1.01x slower                                                         |
| unpickle_list              | 4.65 us                                                      | 4.70 us: 1.01x slower                                                        |
| docutils                   | 2.89 sec                                                     | 2.93 sec: 1.01x slower                                                       |
| xml_etree_generate         | 85.3 ms                                                      | 86.8 ms: 1.02x slower                                                        |
| sqlglot_optimize           | 58.4 ms                                                      | 59.5 ms: 1.02x slower                                                        |
| async_tree_cpu_io_mixed    | 704 ms                                                       | 718 ms: 1.02x slower                                                         |
| asyncio_websockets         | 386 ms                                                       | 394 ms: 1.02x slower                                                         |
| pycparser                  | 1.29 sec                                                     | 1.32 sec: 1.02x slower                                                       |
| sympy_str                  | 305 ms                                                       | 312 ms: 1.02x slower                                                         |
| json                       | 5.17 ms                                                      | 5.29 ms: 1.02x slower                                                        |
| logging_simple             | 6.64 us                                                      | 6.80 us: 1.02x slower                                                        |
| async_tree_memoization     | 554 ms                                                       | 567 ms: 1.02x slower                                                         |
| tornado_http               | 122 ms                                                       | 125 ms: 1.02x slower                                                         |
| async_tree_memoization_tg  | 554 ms                                                       | 568 ms: 1.03x slower                                                         |
| logging_format             | 7.29 us                                                      | 7.51 us: 1.03x slower                                                        |
| pathlib                    | 18.7 ms                                                      | 19.4 ms: 1.03x slower                                                        |
| dask                       | 394 ms                                                       | 407 ms: 1.03x slower                                                         |
| raytrace                   | 301 ms                                                       | 312 ms: 1.04x slower                                                         |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 732 ms: 1.04x slower                                                         |
| mypy2                      | 365 ms                                                       | 379 ms: 1.04x slower                                                         |
| xml_etree_parse            | 147 ms                                                       | 153 ms: 1.04x slower                                                         |
| async_tree_none_tg         | 440 ms                                                       | 459 ms: 1.04x slower                                                         |
| sympy_integrate            | 24.0 ms                                                      | 25.0 ms: 1.04x slower                                                        |
| sqlglot_transpile          | 1.80 ms                                                      | 1.88 ms: 1.04x slower                                                        |
| async_tree_io_tg           | 1.07 sec                                                     | 1.12 sec: 1.04x slower                                                       |
| json_dumps                 | 10.3 ms                                                      | 10.7 ms: 1.04x slower                                                        |
| sqlglot_parse              | 1.41 ms                                                      | 1.47 ms: 1.04x slower                                                        |
| json_loads                 | 24.3 us                                                      | 25.5 us: 1.05x slower                                                        |
| regex_dna                  | 240 ms                                                       | 252 ms: 1.05x slower                                                         |
| async_tree_io              | 1.06 sec                                                     | 1.11 sec: 1.05x slower                                                       |
| logging_silent             | 93.3 ns                                                      | 98.9 ns: 1.06x slower                                                        |
| pickle_list                | 4.22 us                                                      | 4.49 us: 1.06x slower                                                        |
| regex_v8                   | 24.4 ms                                                      | 26.2 ms: 1.07x slower                                                        |
| sympy_expand               | 492 ms                                                       | 527 ms: 1.07x slower                                                         |
| xml_etree_iterparse        | 104 ms                                                       | 111 ms: 1.08x slower                                                         |
| mdp                        | 2.56 sec                                                     | 2.77 sec: 1.09x slower                                                       |
| chameleon                  | 7.27 ms                                                      | 7.93 ms: 1.09x slower                                                        |
| deepcopy_memo              | 36.6 us                                                      | 40.0 us: 1.10x slower                                                        |
| meteor_contest             | 126 ms                                                       | 139 ms: 1.10x slower                                                         |
| python_startup             | 11.7 ms                                                      | 12.8 ms: 1.10x slower                                                        |
| dulwich_log                | 64.9 ms                                                      | 71.3 ms: 1.10x slower                                                        |
| crypto_pyaes               | 82.4 ms                                                      | 90.8 ms: 1.10x slower                                                        |
| scimark_lu                 | 98.6 ms                                                      | 109 ms: 1.11x slower                                                         |
| 2to3                       | 285 ms                                                       | 316 ms: 1.11x slower                                                         |
| pprint_safe_repr           | 808 ms                                                       | 916 ms: 1.13x slower                                                         |
| pprint_pformat             | 1.64 sec                                                     | 1.89 sec: 1.15x slower                                                       |
| telco                      | 7.16 ms                                                      | 8.56 ms: 1.20x slower                                                        |
| unpickle_pure_python       | 210 us                                                       | 252 us: 1.20x slower                                                         |
| richards_super             | 50.8 ms                                                      | 61.4 ms: 1.21x slower                                                        |
| regex_compile              | 145 ms                                                       | 177 ms: 1.23x slower                                                         |
| chaos                      | 64.1 ms                                                      | 78.9 ms: 1.23x slower                                                        |
| richards                   | 45.1 ms                                                      | 55.7 ms: 1.24x slower                                                        |
| coverage                   | 66.3 ms                                                      | 82.9 ms: 1.25x slower                                                        |
| comprehensions             | 21.8 us                                                      | 27.7 us: 1.27x slower                                                        |
| go                         | 149 ms                                                       | 191 ms: 1.28x slower                                                         |
| scimark_monte_carlo        | 69.5 ms                                                      | 90.2 ms: 1.30x slower                                                        |
| python_startup_no_site     | 8.67 ms                                                      | 11.3 ms: 1.30x slower                                                        |
| nqueens                    | 90.1 ms                                                      | 117 ms: 1.30x slower                                                         |
| pyflate                    | 442 ms                                                       | 582 ms: 1.32x slower                                                         |
| float                      | 81.6 ms                                                      | 108 ms: 1.32x slower                                                         |
| tomli_loads                | 2.17 sec                                                     | 2.88 sec: 1.33x slower                                                       |
| nbody                      | 88.2 ms                                                      | 120 ms: 1.37x slower                                                         |
| fannkuch                   | 362 ms                                                       | 505 ms: 1.40x slower                                                         |
| scimark_sor                | 107 ms                                                       | 151 ms: 1.41x slower                                                         |
| scimark_sparse_mat_mult    | 4.49 ms                                                      | 6.60 ms: 1.47x slower                                                        |
| scimark_fft                | 303 ms                                                       | 447 ms: 1.47x slower                                                         |
| mako                       | 10.1 ms                                                      | 16.9 ms: 1.68x slower                                                        |
| deltablue                  | 3.24 ms                                                      | 5.61 ms: 1.73x slower                                                        |
| hexiom                     | 5.97 ms                                                      | 10.6 ms: 1.78x slower                                                        |
| Geometric mean             | (ref)                                                        | 1.10x slower                                                                 |

Benchmark hidden because not significant (7): unpack_sequence, pickle_dict, sqlite_synth, create_gc_cycles, gc_traversal, bench_mp_pool, bench_thread_pool
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.04x
- 95% likely to have a slowdown of 1.04x
- 99% likely to have a slowdown of 1.03x
