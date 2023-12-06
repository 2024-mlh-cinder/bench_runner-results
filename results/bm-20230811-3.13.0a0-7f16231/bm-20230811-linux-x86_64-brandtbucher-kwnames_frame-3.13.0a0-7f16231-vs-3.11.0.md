
# Results vs. 3.11.0

- fork: brandtbucher
- ref: kwnames_frame
- machine: linux-x86_64
- commit hash: 7f16231
- commit date: 2023-08-11
- overall geometric mean: 1.04x faster
- HPT reliability: 65.54%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

Benchmark hidden because not significant (2): docutils, tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230811-linux-x86_64-brandtbucher-kwnames_frame-3.13.0a0-7f16231 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 189 ms: 1.05x faster                                                 |
| nbody          | 93.1 ms                                                | 93.9 ms: 1.01x slower                                                |
| float          | 77.2 ms                                                | 80.2 ms: 1.04x slower                                                |
| Geometric mean | (ref)                                                  | 1.00x slower                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230811-linux-x86_64-brandtbucher-kwnames_frame-3.13.0a0-7f16231 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.55 ms: 1.12x faster                                                |
| regex_compile  | 138 ms                                                 | 137 ms: 1.01x faster                                                 |
| regex_dna      | 204 ms                                                 | 213 ms: 1.05x slower                                                 |
| regex_v8       | 22.0 ms                                                | 25.1 ms: 1.14x slower                                                |
| Geometric mean | (ref)                                                  | 1.01x slower                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230811-linux-x86_64-brandtbucher-kwnames_frame-3.13.0a0-7f16231 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.78 ms: 1.29x faster                                                |
| unpickle_pure_python | 228 us                                                 | 216 us: 1.06x faster                                                 |
| tomli_loads          | 2.22 sec                                               | 2.12 sec: 1.05x faster                                               |
| json_loads           | 26.5 us                                                | 25.5 us: 1.04x faster                                                |
| xml_etree_parse      | 158 ms                                                 | 153 ms: 1.03x faster                                                 |
| pickle_pure_python   | 306 us                                                 | 303 us: 1.01x faster                                                 |
| pickle               | 10.1 us                                                | 10.4 us: 1.04x slower                                                |
| pickle_list          | 4.11 us                                                | 4.38 us: 1.07x slower                                                |
| xml_etree_process    | 53.9 ms                                                | 57.9 ms: 1.08x slower                                                |
| unpickle             | 13.7 us                                                | 15.0 us: 1.10x slower                                                |
| xml_etree_generate   | 76.2 ms                                                | 84.6 ms: 1.11x slower                                                |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                         |

Benchmark hidden because not significant (3): xml_etree_iterparse, unpickle_list, pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230811-linux-x86_64-brandtbucher-kwnames_frame-3.13.0a0-7f16231 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 8.52 ms                                                | 9.42 ms: 1.11x slower                                                |
| python_startup_no_site | 6.01 ms                                                | 6.90 ms: 1.15x slower                                                |
| Geometric mean         | (ref)                                                  | 1.13x slower                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230811-linux-x86_64-brandtbucher-kwnames_frame-3.13.0a0-7f16231 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 10.8 ms: 1.07x slower                                                |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230811-linux-x86_64-brandtbucher-kwnames_frame-3.13.0a0-7f16231 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 143 us: 3.40x faster                                                 |
| generators               | 73.5 ms                                                | 29.3 ms: 2.51x faster                                                |
| asyncio_tcp              | 922 ms                                                 | 489 ms: 1.89x faster                                                 |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.79 sec: 1.75x faster                                               |
| json_dumps               | 12.6 ms                                                | 9.78 ms: 1.29x faster                                                |
| mypy2                    | 420 ms                                                 | 340 ms: 1.24x faster                                                 |
| async_tree_none          | 526 ms                                                 | 448 ms: 1.18x faster                                                 |
| coverage                 | 100 ms                                                 | 86.0 ms: 1.16x faster                                                |
| chaos                    | 69.2 ms                                                | 61.0 ms: 1.13x faster                                                |
| regex_effbot             | 3.99 ms                                                | 3.55 ms: 1.12x faster                                                |
| deltablue                | 3.67 ms                                                | 3.32 ms: 1.11x faster                                                |
| coroutines               | 25.5 ms                                                | 23.1 ms: 1.11x faster                                                |
| sqlglot_parse            | 1.40 ms                                                | 1.28 ms: 1.10x faster                                                |
| async_tree_memoization   | 627 ms                                                 | 580 ms: 1.08x faster                                                 |
| raytrace                 | 297 ms                                                 | 276 ms: 1.08x faster                                                 |
| sqlglot_transpile        | 1.70 ms                                                | 1.60 ms: 1.07x faster                                                |
| crypto_pyaes             | 74.7 ms                                                | 70.2 ms: 1.06x faster                                                |
| comprehensions           | 22.4 us                                                | 21.1 us: 1.06x faster                                                |
| unpack_sequence          | 43.1 ns                                                | 40.6 ns: 1.06x faster                                                |
| unpickle_pure_python     | 228 us                                                 | 216 us: 1.06x faster                                                 |
| async_tree_io            | 1.30 sec                                               | 1.23 sec: 1.05x faster                                               |
| hexiom                   | 6.37 ms                                                | 6.07 ms: 1.05x faster                                                |
| tomli_loads              | 2.22 sec                                               | 2.12 sec: 1.05x faster                                               |
| pidigits                 | 198 ms                                                 | 189 ms: 1.05x faster                                                 |
| json_loads               | 26.5 us                                                | 25.5 us: 1.04x faster                                                |
| richards_super           | 56.8 ms                                                | 54.8 ms: 1.04x faster                                                |
| xml_etree_parse          | 158 ms                                                 | 153 ms: 1.03x faster                                                 |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 717 ms: 1.03x faster                                                 |
| mdp                      | 2.62 sec                                               | 2.55 sec: 1.03x faster                                               |
| sqlglot_normalize        | 108 ms                                                 | 105 ms: 1.03x faster                                                 |
| scimark_monte_carlo      | 68.1 ms                                                | 66.5 ms: 1.02x faster                                                |
| logging_format           | 6.68 us                                                | 6.56 us: 1.02x faster                                                |
| nqueens                  | 83.4 ms                                                | 81.9 ms: 1.02x faster                                                |
| pycparser                | 1.18 sec                                               | 1.17 sec: 1.01x faster                                               |
| pickle_pure_python       | 306 us                                                 | 303 us: 1.01x faster                                                 |
| regex_compile            | 138 ms                                                 | 137 ms: 1.01x faster                                                 |
| logging_simple           | 6.03 us                                                | 5.98 us: 1.01x faster                                                |
| sqlglot_optimize         | 53.1 ms                                                | 52.8 ms: 1.01x faster                                                |
| bench_thread_pool        | 819 us                                                 | 825 us: 1.01x slower                                                 |
| nbody                    | 93.1 ms                                                | 93.9 ms: 1.01x slower                                                |
| deepcopy_memo            | 37.0 us                                                | 37.6 us: 1.02x slower                                                |
| fannkuch                 | 388 ms                                                 | 394 ms: 1.02x slower                                                 |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.58 ms: 1.02x slower                                                |
| pprint_pformat           | 1.46 sec                                               | 1.49 sec: 1.02x slower                                               |
| scimark_sor              | 118 ms                                                 | 122 ms: 1.03x slower                                                 |
| deepcopy                 | 342 us                                                 | 354 us: 1.04x slower                                                 |
| pickle                   | 10.1 us                                                | 10.4 us: 1.04x slower                                                |
| logging_silent           | 101 ns                                                 | 105 ns: 1.04x slower                                                 |
| pprint_safe_repr         | 701 ms                                                 | 729 ms: 1.04x slower                                                 |
| float                    | 77.2 ms                                                | 80.2 ms: 1.04x slower                                                |
| pathlib                  | 18.2 ms                                                | 19.0 ms: 1.04x slower                                                |
| richards                 | 45.7 ms                                                | 47.6 ms: 1.04x slower                                                |
| dulwich_log              | 63.7 ms                                                | 66.5 ms: 1.04x slower                                                |
| regex_dna                | 204 ms                                                 | 213 ms: 1.05x slower                                                 |
| pickle_list              | 4.11 us                                                | 4.38 us: 1.07x slower                                                |
| pyflate                  | 418 ms                                                 | 446 ms: 1.07x slower                                                 |
| mako                     | 10.1 ms                                                | 10.8 ms: 1.07x slower                                                |
| xml_etree_process        | 53.9 ms                                                | 57.9 ms: 1.08x slower                                                |
| gc_traversal             | 4.02 ms                                                | 4.33 ms: 1.08x slower                                                |
| deepcopy_reduce          | 2.94 us                                                | 3.16 us: 1.08x slower                                                |
| scimark_fft              | 328 ms                                                 | 354 ms: 1.08x slower                                                 |
| sqlite_synth             | 2.52 us                                                | 2.74 us: 1.09x slower                                                |
| unpickle                 | 13.7 us                                                | 15.0 us: 1.10x slower                                                |
| spectral_norm            | 100 ms                                                 | 110 ms: 1.10x slower                                                 |
| python_startup           | 8.52 ms                                                | 9.42 ms: 1.11x slower                                                |
| xml_etree_generate       | 76.2 ms                                                | 84.6 ms: 1.11x slower                                                |
| regex_v8                 | 22.0 ms                                                | 25.1 ms: 1.14x slower                                                |
| python_startup_no_site   | 6.01 ms                                                | 6.90 ms: 1.15x slower                                                |
| async_generators         | 368 ms                                                 | 443 ms: 1.20x slower                                                 |
| telco                    | 6.58 ms                                                | 8.01 ms: 1.22x slower                                                |
| dask                     | 360 ms                                                 | 525 ms: 1.46x slower                                                 |
| Geometric mean           | (ref)                                                  | 1.04x faster                                                         |

Benchmark hidden because not significant (11): json, xml_etree_iterparse, unpickle_list, meteor_contest, go, scimark_lu, bench_mp_pool, tornado_http, pickle_dict, create_gc_cycles, docutils
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 65.54% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
