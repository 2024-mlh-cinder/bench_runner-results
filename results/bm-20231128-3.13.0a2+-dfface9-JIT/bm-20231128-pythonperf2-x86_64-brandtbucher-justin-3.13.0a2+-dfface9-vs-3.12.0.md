
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: dfface9
- commit date: 2023-11-28
- overall geometric mean: 1.05x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-pythonperf2-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 301 ms: 1.06x slower                                                 |
| chameleon      | 7.27 ms                                                      | 7.71 ms: 1.06x slower                                                |
| docutils       | 2.89 sec                                                     | 2.86 sec: 1.01x faster                                               |
| tornado_http   | 122 ms                                                       | 120 ms: 1.02x faster                                                 |
| Geometric mean | (ref)                                                        | 1.02x slower                                                         |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-pythonperf2-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| async_tree_none            | 459 ms                                                       | 443 ms: 1.04x faster                                                 |
| async_tree_none_tg         | 440 ms                                                       | 450 ms: 1.02x slower                                                 |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 722 ms: 1.02x slower                                                 |
| async_tree_io_tg           | 1.07 sec                                                     | 1.11 sec: 1.03x slower                                               |
| async_tree_io              | 1.06 sec                                                     | 1.09 sec: 1.04x slower                                               |
| async_tree_memoization_tg  | 554 ms                                                       | 580 ms: 1.05x slower                                                 |
| Geometric mean             | (ref)                                                        | 1.02x slower                                                         |

Benchmark hidden because not significant (2): async_tree_cpu_io_mixed, async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-pythonperf2-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| pidigits       | 264 ms                                                       | 265 ms: 1.00x slower                                                 |
| nbody          | 88.2 ms                                                      | 104 ms: 1.18x slower                                                 |
| Geometric mean | (ref)                                                        | 1.05x slower                                                         |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-pythonperf2-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.51 ms: 1.03x faster                                                |
| regex_v8       | 24.4 ms                                                      | 24.7 ms: 1.01x slower                                                |
| regex_dna      | 240 ms                                                       | 246 ms: 1.02x slower                                                 |
| regex_compile  | 145 ms                                                       | 149 ms: 1.03x slower                                                 |
| Geometric mean | (ref)                                                        | 1.01x slower                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-pythonperf2-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| pickle_pure_python   | 319 us                                                       | 306 us: 1.05x faster                                                 |
| pickle               | 10.0 us                                                      | 9.95 us: 1.01x faster                                                |
| xml_etree_process    | 58.3 ms                                                      | 58.8 ms: 1.01x slower                                                |
| xml_etree_generate   | 85.3 ms                                                      | 86.3 ms: 1.01x slower                                                |
| pickle_list          | 4.22 us                                                      | 4.26 us: 1.01x slower                                                |
| xml_etree_iterparse  | 104 ms                                                       | 106 ms: 1.02x slower                                                 |
| xml_etree_parse      | 147 ms                                                       | 151 ms: 1.03x slower                                                 |
| pickle_dict          | 32.0 us                                                      | 33.1 us: 1.03x slower                                                |
| unpickle_list        | 4.65 us                                                      | 4.82 us: 1.04x slower                                                |
| tomli_loads          | 2.17 sec                                                     | 2.25 sec: 1.04x slower                                               |
| json_dumps           | 10.3 ms                                                      | 10.8 ms: 1.05x slower                                                |
| json_loads           | 24.3 us                                                      | 25.6 us: 1.06x slower                                                |
| unpickle_pure_python | 210 us                                                       | 236 us: 1.13x slower                                                 |
| Geometric mean       | (ref)                                                        | 1.03x slower                                                         |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-pythonperf2-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 12.9 ms: 1.11x slower                                                |
| python_startup_no_site | 8.67 ms                                                      | 11.4 ms: 1.31x slower                                                |
| Geometric mean         | (ref)                                                        | 1.21x slower                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-pythonperf2-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 10.1 ms                                                      | 11.1 ms: 1.10x slower                                                |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-pythonperf2-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| unpack_sequence            | 54.5 ns                                                      | 44.8 ns: 1.22x faster                                                |
| typing_runtime_protocols   | 150 us                                                       | 132 us: 1.14x faster                                                 |
| comprehensions             | 21.8 us                                                      | 20.2 us: 1.08x faster                                                |
| generators                 | 37.3 ms                                                      | 34.7 ms: 1.07x faster                                                |
| scimark_sparse_mat_mult    | 4.49 ms                                                      | 4.29 ms: 1.05x faster                                                |
| pickle_pure_python         | 319 us                                                       | 306 us: 1.05x faster                                                 |
| asyncio_tcp                | 380 ms                                                       | 366 ms: 1.04x faster                                                 |
| async_tree_none            | 459 ms                                                       | 443 ms: 1.04x faster                                                 |
| raytrace                   | 301 ms                                                       | 292 ms: 1.03x faster                                                 |
| regex_effbot               | 3.61 ms                                                      | 3.51 ms: 1.03x faster                                                |
| sympy_sum                  | 163 ms                                                       | 158 ms: 1.03x faster                                                 |
| tornado_http               | 122 ms                                                       | 120 ms: 1.02x faster                                                 |
| sympy_str                  | 305 ms                                                       | 300 ms: 1.02x faster                                                 |
| crypto_pyaes               | 82.4 ms                                                      | 81.3 ms: 1.01x faster                                                |
| logging_simple             | 6.64 us                                                      | 6.56 us: 1.01x faster                                                |
| async_generators           | 385 ms                                                       | 381 ms: 1.01x faster                                                 |
| coroutines                 | 23.1 ms                                                      | 22.8 ms: 1.01x faster                                                |
| docutils                   | 2.89 sec                                                     | 2.86 sec: 1.01x faster                                               |
| pickle                     | 10.0 us                                                      | 9.95 us: 1.01x faster                                                |
| deepcopy_reduce            | 3.41 us                                                      | 3.38 us: 1.01x faster                                                |
| sqlglot_parse              | 1.41 ms                                                      | 1.40 ms: 1.00x faster                                                |
| pidigits                   | 264 ms                                                       | 265 ms: 1.00x slower                                                 |
| sympy_integrate            | 24.0 ms                                                      | 24.2 ms: 1.01x slower                                                |
| asyncio_websockets         | 386 ms                                                       | 389 ms: 1.01x slower                                                 |
| xml_etree_process          | 58.3 ms                                                      | 58.8 ms: 1.01x slower                                                |
| sqlite_synth               | 2.72 us                                                      | 2.74 us: 1.01x slower                                                |
| json                       | 5.17 ms                                                      | 5.22 ms: 1.01x slower                                                |
| pathlib                    | 18.7 ms                                                      | 18.9 ms: 1.01x slower                                                |
| xml_etree_generate         | 85.3 ms                                                      | 86.3 ms: 1.01x slower                                                |
| pickle_list                | 4.22 us                                                      | 4.26 us: 1.01x slower                                                |
| sqlglot_normalize          | 119 ms                                                       | 121 ms: 1.01x slower                                                 |
| regex_v8                   | 24.4 ms                                                      | 24.7 ms: 1.01x slower                                                |
| sqlglot_transpile          | 1.80 ms                                                      | 1.83 ms: 1.01x slower                                                |
| logging_format             | 7.29 us                                                      | 7.40 us: 1.01x slower                                                |
| mdp                        | 2.56 sec                                                     | 2.59 sec: 1.01x slower                                               |
| dask                       | 394 ms                                                       | 400 ms: 1.02x slower                                                 |
| sympy_expand               | 492 ms                                                       | 502 ms: 1.02x slower                                                 |
| async_tree_none_tg         | 440 ms                                                       | 450 ms: 1.02x slower                                                 |
| xml_etree_iterparse        | 104 ms                                                       | 106 ms: 1.02x slower                                                 |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 722 ms: 1.02x slower                                                 |
| regex_dna                  | 240 ms                                                       | 246 ms: 1.02x slower                                                 |
| pycparser                  | 1.29 sec                                                     | 1.32 sec: 1.02x slower                                               |
| deepcopy                   | 371 us                                                       | 380 us: 1.02x slower                                                 |
| regex_compile              | 145 ms                                                       | 149 ms: 1.03x slower                                                 |
| xml_etree_parse            | 147 ms                                                       | 151 ms: 1.03x slower                                                 |
| async_tree_io_tg           | 1.07 sec                                                     | 1.11 sec: 1.03x slower                                               |
| pickle_dict                | 32.0 us                                                      | 33.1 us: 1.03x slower                                                |
| dulwich_log                | 64.9 ms                                                      | 67.1 ms: 1.03x slower                                                |
| deepcopy_memo              | 36.6 us                                                      | 37.8 us: 1.03x slower                                                |
| async_tree_io              | 1.06 sec                                                     | 1.09 sec: 1.04x slower                                               |
| unpickle_list              | 4.65 us                                                      | 4.82 us: 1.04x slower                                                |
| tomli_loads                | 2.17 sec                                                     | 2.25 sec: 1.04x slower                                               |
| scimark_lu                 | 98.6 ms                                                      | 103 ms: 1.05x slower                                                 |
| async_tree_memoization_tg  | 554 ms                                                       | 580 ms: 1.05x slower                                                 |
| json_dumps                 | 10.3 ms                                                      | 10.8 ms: 1.05x slower                                                |
| json_loads                 | 24.3 us                                                      | 25.6 us: 1.06x slower                                                |
| logging_silent             | 93.3 ns                                                      | 98.6 ns: 1.06x slower                                                |
| gc_traversal               | 3.70 ms                                                      | 3.92 ms: 1.06x slower                                                |
| 2to3                       | 285 ms                                                       | 301 ms: 1.06x slower                                                 |
| sqlglot_optimize           | 58.4 ms                                                      | 61.8 ms: 1.06x slower                                                |
| meteor_contest             | 126 ms                                                       | 134 ms: 1.06x slower                                                 |
| chameleon                  | 7.27 ms                                                      | 7.71 ms: 1.06x slower                                                |
| pprint_safe_repr           | 808 ms                                                       | 864 ms: 1.07x slower                                                 |
| spectral_norm              | 93.9 ms                                                      | 102 ms: 1.08x slower                                                 |
| pprint_pformat             | 1.64 sec                                                     | 1.78 sec: 1.08x slower                                               |
| mako                       | 10.1 ms                                                      | 11.1 ms: 1.10x slower                                                |
| python_startup             | 11.7 ms                                                      | 12.9 ms: 1.11x slower                                                |
| richards_super             | 50.8 ms                                                      | 56.3 ms: 1.11x slower                                                |
| richards                   | 45.1 ms                                                      | 50.1 ms: 1.11x slower                                                |
| chaos                      | 64.1 ms                                                      | 72.1 ms: 1.13x slower                                                |
| unpickle_pure_python       | 210 us                                                       | 236 us: 1.13x slower                                                 |
| deltablue                  | 3.24 ms                                                      | 3.73 ms: 1.15x slower                                                |
| nqueens                    | 90.1 ms                                                      | 104 ms: 1.15x slower                                                 |
| fannkuch                   | 362 ms                                                       | 420 ms: 1.16x slower                                                 |
| go                         | 149 ms                                                       | 173 ms: 1.16x slower                                                 |
| telco                      | 7.16 ms                                                      | 8.33 ms: 1.16x slower                                                |
| pyflate                    | 442 ms                                                       | 517 ms: 1.17x slower                                                 |
| nbody                      | 88.2 ms                                                      | 104 ms: 1.18x slower                                                 |
| scimark_monte_carlo        | 69.5 ms                                                      | 82.1 ms: 1.18x slower                                                |
| scimark_fft                | 303 ms                                                       | 364 ms: 1.20x slower                                                 |
| coverage                   | 66.3 ms                                                      | 81.3 ms: 1.23x slower                                                |
| hexiom                     | 5.97 ms                                                      | 7.72 ms: 1.29x slower                                                |
| python_startup_no_site     | 8.67 ms                                                      | 11.4 ms: 1.31x slower                                                |
| scimark_sor                | 107 ms                                                       | 152 ms: 1.43x slower                                                 |
| mypy2                      | 365 ms                                                       | 885 ms: 2.42x slower                                                 |
| Geometric mean             | (ref)                                                        | 1.05x slower                                                         |

Benchmark hidden because not significant (8): float, asyncio_tcp_ssl, create_gc_cycles, unpickle, async_tree_cpu_io_mixed, async_tree_memoization, bench_mp_pool, bench_thread_pool
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
