
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: dfface9
- commit date: 2023-11-28
- overall geometric mean: 1.01x faster \*
- HPT reliability: 92.84%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-pythonperf1-amd64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 233 ms: 1.12x slower                                                |
| chameleon      | 5.35 ms                                                     | 5.29 ms: 1.01x faster                                               |
| docutils       | 1.59 sec                                                    | 1.66 sec: 1.04x slower                                              |
| tornado_http   | 89.9 ms                                                     | 93.3 ms: 1.04x slower                                               |
| Geometric mean | (ref)                                                       | 1.05x slower                                                        |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-pythonperf1-amd64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| async_tree_none            | 314 ms                                                      | 286 ms: 1.10x faster                                                |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 482 ms: 1.03x faster                                                |
| async_tree_memoization     | 367 ms                                                      | 359 ms: 1.02x faster                                                |
| async_tree_io_tg           | 795 ms                                                      | 816 ms: 1.03x slower                                                |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 517 ms: 1.03x slower                                                |
| async_tree_io              | 753 ms                                                      | 775 ms: 1.03x slower                                                |
| Geometric mean             | (ref)                                                       | 1.01x faster                                                        |

Benchmark hidden because not significant (2): async_tree_none_tg, async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-pythonperf1-amd64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| nbody          | 69.3 ms                                                     | 60.1 ms: 1.15x faster                                               |
| float          | 54.4 ms                                                     | 50.0 ms: 1.09x faster                                               |
| pidigits       | 149 ms                                                      | 150 ms: 1.01x slower                                                |
| Geometric mean | (ref)                                                       | 1.07x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-pythonperf1-amd64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 87.7 ms: 1.04x faster                                               |
| regex_dna      | 121 ms                                                      | 124 ms: 1.03x slower                                                |
| regex_effbot   | 1.52 ms                                                     | 1.79 ms: 1.18x slower                                               |
| regex_v8       | 13.7 ms                                                     | 21.3 ms: 1.56x slower                                               |
| Geometric mean | (ref)                                                       | 1.16x slower                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-pythonperf1-amd64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 6.13 ms: 1.29x faster                                               |
| pickle_pure_python   | 207 us                                                      | 193 us: 1.07x faster                                                |
| unpickle_pure_python | 152 us                                                      | 147 us: 1.04x faster                                                |
| tomli_loads          | 1.42 sec                                                    | 1.38 sec: 1.03x faster                                              |
| xml_etree_parse      | 94.5 ms                                                     | 96.0 ms: 1.02x slower                                               |
| xml_etree_iterparse  | 63.0 ms                                                     | 64.9 ms: 1.03x slower                                               |
| unpickle_list        | 2.57 us                                                     | 2.69 us: 1.05x slower                                               |
| unpickle             | 7.82 us                                                     | 8.23 us: 1.05x slower                                               |
| pickle_dict          | 17.8 us                                                     | 19.0 us: 1.07x slower                                               |
| xml_etree_process    | 37.0 ms                                                     | 39.7 ms: 1.07x slower                                               |
| pickle               | 6.53 us                                                     | 7.11 us: 1.09x slower                                               |
| xml_etree_generate   | 52.2 ms                                                     | 58.0 ms: 1.11x slower                                               |
| json_loads           | 12.9 us                                                     | 14.5 us: 1.12x slower                                               |
| pickle_list          | 2.68 us                                                     | 3.26 us: 1.22x slower                                               |
| Geometric mean       | (ref)                                                       | 1.03x slower                                                        |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-pythonperf1-amd64-brandtbucher-justin-3.13.0a2+-dfface9 |
|------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.8 ms: 1.10x slower                                               |
| python_startup_no_site | 15.5 ms                                                     | 18.9 ms: 1.22x slower                                               |
| Geometric mean         | (ref)                                                       | 1.16x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-pythonperf1-amd64-brandtbucher-justin-3.13.0a2+-dfface9 |
|-----------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 6.37 ms: 1.18x faster                                               |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-pythonperf1-amd64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 82.7 us: 3.87x faster                                               |
| generators                 | 34.0 ms                                                     | 25.7 ms: 1.32x faster                                               |
| comprehensions             | 15.6 us                                                     | 11.8 us: 1.32x faster                                               |
| json_dumps                 | 7.90 ms                                                     | 6.13 ms: 1.29x faster                                               |
| deltablue                  | 2.63 ms                                                     | 2.09 ms: 1.25x faster                                               |
| asyncio_tcp                | 614 ms                                                      | 496 ms: 1.24x faster                                                |
| unpack_sequence            | 47.0 ns                                                     | 38.3 ns: 1.22x faster                                               |
| mdp                        | 1.73 sec                                                    | 1.41 sec: 1.22x faster                                              |
| raytrace                   | 211 ms                                                      | 177 ms: 1.19x faster                                                |
| mako                       | 7.55 ms                                                     | 6.37 ms: 1.18x faster                                               |
| richards_super             | 37.9 ms                                                     | 32.1 ms: 1.18x faster                                               |
| nbody                      | 69.3 ms                                                     | 60.1 ms: 1.15x faster                                               |
| asyncio_tcp_ssl            | 2.02 sec                                                    | 1.77 sec: 1.14x faster                                              |
| sympy_sum                  | 100.0 ms                                                    | 87.8 ms: 1.14x faster                                               |
| sqlite_synth               | 1.79 us                                                     | 1.60 us: 1.12x faster                                               |
| logging_silent             | 70.7 ns                                                     | 64.0 ns: 1.10x faster                                               |
| async_tree_none            | 314 ms                                                      | 286 ms: 1.10x faster                                                |
| sqlglot_parse              | 939 us                                                      | 862 us: 1.09x faster                                                |
| float                      | 54.4 ms                                                     | 50.0 ms: 1.09x faster                                               |
| richards                   | 30.8 ms                                                     | 28.5 ms: 1.08x faster                                               |
| pickle_pure_python         | 207 us                                                      | 193 us: 1.07x faster                                                |
| deepcopy_memo              | 25.5 us                                                     | 23.8 us: 1.07x faster                                               |
| chaos                      | 46.8 ms                                                     | 43.7 ms: 1.07x faster                                               |
| sympy_str                  | 184 ms                                                      | 172 ms: 1.07x faster                                                |
| spectral_norm              | 69.9 ms                                                     | 65.9 ms: 1.06x faster                                               |
| sqlglot_transpile          | 1.15 ms                                                     | 1.10 ms: 1.04x faster                                               |
| unpickle_pure_python       | 152 us                                                      | 147 us: 1.04x faster                                                |
| regex_compile              | 90.8 ms                                                     | 87.7 ms: 1.04x faster                                               |
| logging_format             | 7.06 us                                                     | 6.82 us: 1.03x faster                                               |
| sympy_expand               | 299 ms                                                      | 289 ms: 1.03x faster                                                |
| scimark_lu                 | 62.3 ms                                                     | 60.3 ms: 1.03x faster                                               |
| go                         | 98.8 ms                                                     | 95.8 ms: 1.03x faster                                               |
| hexiom                     | 4.51 ms                                                     | 4.38 ms: 1.03x faster                                               |
| crypto_pyaes               | 48.2 ms                                                     | 46.8 ms: 1.03x faster                                               |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 482 ms: 1.03x faster                                                |
| tomli_loads                | 1.42 sec                                                    | 1.38 sec: 1.03x faster                                              |
| async_tree_memoization     | 367 ms                                                      | 359 ms: 1.02x faster                                                |
| logging_simple             | 6.60 us                                                     | 6.48 us: 1.02x faster                                               |
| chameleon                  | 5.35 ms                                                     | 5.29 ms: 1.01x faster                                               |
| coroutines                 | 14.7 ms                                                     | 14.8 ms: 1.01x slower                                               |
| pidigits                   | 149 ms                                                      | 150 ms: 1.01x slower                                                |
| xml_etree_parse            | 94.5 ms                                                     | 96.0 ms: 1.02x slower                                               |
| deepcopy                   | 242 us                                                      | 247 us: 1.02x slower                                                |
| dulwich_log                | 44.1 ms                                                     | 45.1 ms: 1.02x slower                                               |
| regex_dna                  | 121 ms                                                      | 124 ms: 1.03x slower                                                |
| meteor_contest             | 75.0 ms                                                     | 76.9 ms: 1.03x slower                                               |
| async_tree_io_tg           | 795 ms                                                      | 816 ms: 1.03x slower                                                |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 517 ms: 1.03x slower                                                |
| async_tree_io              | 753 ms                                                      | 775 ms: 1.03x slower                                                |
| xml_etree_iterparse        | 63.0 ms                                                     | 64.9 ms: 1.03x slower                                               |
| scimark_sparse_mat_mult    | 2.59 ms                                                     | 2.67 ms: 1.03x slower                                               |
| fannkuch                   | 248 ms                                                      | 256 ms: 1.03x slower                                                |
| sqlglot_normalize          | 191 ms                                                      | 198 ms: 1.04x slower                                                |
| tornado_http               | 89.9 ms                                                     | 93.3 ms: 1.04x slower                                               |
| bench_thread_pool          | 847 us                                                      | 882 us: 1.04x slower                                                |
| docutils                   | 1.59 sec                                                    | 1.66 sec: 1.04x slower                                              |
| sqlglot_optimize           | 35.1 ms                                                     | 36.7 ms: 1.05x slower                                               |
| pprint_pformat             | 1.06 sec                                                    | 1.11 sec: 1.05x slower                                              |
| unpickle_list              | 2.57 us                                                     | 2.69 us: 1.05x slower                                               |
| gc_traversal               | 1.46 ms                                                     | 1.53 ms: 1.05x slower                                               |
| dask                       | 262 ms                                                      | 276 ms: 1.05x slower                                                |
| unpickle                   | 7.82 us                                                     | 8.23 us: 1.05x slower                                               |
| deepcopy_reduce            | 2.07 us                                                     | 2.19 us: 1.06x slower                                               |
| pprint_safe_repr           | 519 ms                                                      | 548 ms: 1.06x slower                                                |
| pycparser                  | 705 ms                                                      | 747 ms: 1.06x slower                                                |
| scimark_fft                | 181 ms                                                      | 192 ms: 1.06x slower                                                |
| create_gc_cycles           | 706 us                                                      | 752 us: 1.07x slower                                                |
| scimark_monte_carlo        | 44.6 ms                                                     | 47.7 ms: 1.07x slower                                               |
| pickle_dict                | 17.8 us                                                     | 19.0 us: 1.07x slower                                               |
| xml_etree_process          | 37.0 ms                                                     | 39.7 ms: 1.07x slower                                               |
| pickle                     | 6.53 us                                                     | 7.11 us: 1.09x slower                                               |
| coverage                   | 43.0 ms                                                     | 47.0 ms: 1.09x slower                                               |
| scimark_sor                | 76.4 ms                                                     | 83.9 ms: 1.10x slower                                               |
| bench_mp_pool              | 61.1 ms                                                     | 67.4 ms: 1.10x slower                                               |
| python_startup             | 18.8 ms                                                     | 20.8 ms: 1.10x slower                                               |
| xml_etree_generate         | 52.2 ms                                                     | 58.0 ms: 1.11x slower                                               |
| 2to3                       | 207 ms                                                      | 233 ms: 1.12x slower                                                |
| json_loads                 | 12.9 us                                                     | 14.5 us: 1.12x slower                                               |
| regex_effbot               | 1.52 ms                                                     | 1.79 ms: 1.18x slower                                               |
| pathlib                    | 69.4 ms                                                     | 82.0 ms: 1.18x slower                                               |
| python_startup_no_site     | 15.5 ms                                                     | 18.9 ms: 1.22x slower                                               |
| telco                      | 3.93 ms                                                     | 4.78 ms: 1.22x slower                                               |
| pickle_list                | 2.68 us                                                     | 3.26 us: 1.22x slower                                               |
| async_generators           | 181 ms                                                      | 255 ms: 1.41x slower                                                |
| regex_v8                   | 13.7 ms                                                     | 21.3 ms: 1.56x slower                                               |
| mypy2                      | 226 ms                                                      | 450 ms: 1.99x slower                                                |
| Geometric mean             | (ref)                                                       | 1.01x faster                                                        |

Benchmark hidden because not significant (6): async_tree_none_tg, nqueens, pyflate, sympy_integrate, async_tree_memoization_tg, json
Ignored benchmarks (10) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 92.84% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
