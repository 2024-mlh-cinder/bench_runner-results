
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin_operands
- machine: linux-x86_64
- commit hash: fb96638
- commit date: 2023-09-24
- overall geometric mean: 1.02x faster
- HPT reliability: 90.02%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.71 sec: 1.03x slower                                                 |
| tornado_http   | 96.3 ms                                                | 97.1 ms: 1.01x slower                                                  |
| Geometric mean | (ref)                                                  | 1.02x slower                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 189 ms: 1.05x faster                                                   |
| nbody          | 93.1 ms                                                | 97.5 ms: 1.05x slower                                                  |
| float          | 77.2 ms                                                | 83.1 ms: 1.08x slower                                                  |
| Geometric mean | (ref)                                                  | 1.02x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.54 ms: 1.13x faster                                                  |
| regex_dna      | 204 ms                                                 | 206 ms: 1.01x slower                                                   |
| regex_compile  | 138 ms                                                 | 145 ms: 1.05x slower                                                   |
| regex_v8       | 22.0 ms                                                | 23.6 ms: 1.07x slower                                                  |
| Geometric mean | (ref)                                                  | 1.00x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.93 ms: 1.27x faster                                                  |
| tomli_loads          | 2.22 sec                                               | 2.12 sec: 1.05x faster                                                 |
| xml_etree_parse      | 158 ms                                                 | 152 ms: 1.04x faster                                                   |
| json_loads           | 26.5 us                                                | 25.5 us: 1.04x faster                                                  |
| pickle_pure_python   | 306 us                                                 | 300 us: 1.02x faster                                                   |
| pickle_dict          | 31.1 us                                                | 30.7 us: 1.02x faster                                                  |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.01x faster                                                   |
| unpickle_pure_python | 228 us                                                 | 230 us: 1.01x slower                                                   |
| unpickle             | 13.7 us                                                | 14.5 us: 1.06x slower                                                  |
| xml_etree_process    | 53.9 ms                                                | 57.6 ms: 1.07x slower                                                  |
| xml_etree_generate   | 76.2 ms                                                | 83.7 ms: 1.10x slower                                                  |
| pickle_list          | 4.11 us                                                | 4.64 us: 1.13x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.00x faster                                                           |

Benchmark hidden because not significant (2): unpickle_list, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.87 ms: 1.14x slower                                                  |
| python_startup         | 8.52 ms                                                | 10.1 ms: 1.18x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.16x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 11.0 ms: 1.09x slower                                                  |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 146 us: 3.34x faster                                                   |
| generators               | 73.5 ms                                                | 29.0 ms: 2.53x faster                                                  |
| asyncio_tcp              | 922 ms                                                 | 502 ms: 1.84x faster                                                   |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.81 sec: 1.74x faster                                                 |
| json_dumps               | 12.6 ms                                                | 9.93 ms: 1.27x faster                                                  |
| mypy2                    | 420 ms                                                 | 351 ms: 1.20x faster                                                   |
| async_tree_none          | 526 ms                                                 | 443 ms: 1.19x faster                                                   |
| coverage                 | 100 ms                                                 | 84.8 ms: 1.18x faster                                                  |
| regex_effbot             | 3.99 ms                                                | 3.54 ms: 1.13x faster                                                  |
| coroutines               | 25.5 ms                                                | 22.7 ms: 1.13x faster                                                  |
| async_tree_memoization   | 627 ms                                                 | 569 ms: 1.10x faster                                                   |
| sqlglot_parse            | 1.40 ms                                                | 1.28 ms: 1.09x faster                                                  |
| async_tree_io            | 1.30 sec                                               | 1.19 sec: 1.09x faster                                                 |
| raytrace                 | 297 ms                                                 | 276 ms: 1.08x faster                                                   |
| deltablue                | 3.67 ms                                                | 3.45 ms: 1.06x faster                                                  |
| sqlglot_transpile        | 1.70 ms                                                | 1.61 ms: 1.06x faster                                                  |
| pidigits                 | 198 ms                                                 | 189 ms: 1.05x faster                                                   |
| tomli_loads              | 2.22 sec                                               | 2.12 sec: 1.05x faster                                                 |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 706 ms: 1.05x faster                                                   |
| crypto_pyaes             | 74.7 ms                                                | 71.5 ms: 1.04x faster                                                  |
| xml_etree_parse          | 158 ms                                                 | 152 ms: 1.04x faster                                                   |
| richards_super           | 56.8 ms                                                | 54.4 ms: 1.04x faster                                                  |
| gc_traversal             | 4.02 ms                                                | 3.86 ms: 1.04x faster                                                  |
| chaos                    | 69.2 ms                                                | 66.6 ms: 1.04x faster                                                  |
| json_loads               | 26.5 us                                                | 25.5 us: 1.04x faster                                                  |
| pickle_pure_python       | 306 us                                                 | 300 us: 1.02x faster                                                   |
| pickle_dict              | 31.1 us                                                | 30.7 us: 1.02x faster                                                  |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.01x faster                                                   |
| mdp                      | 2.62 sec                                               | 2.60 sec: 1.01x faster                                                 |
| tornado_http             | 96.3 ms                                                | 97.1 ms: 1.01x slower                                                  |
| unpickle_pure_python     | 228 us                                                 | 230 us: 1.01x slower                                                   |
| logging_simple           | 6.03 us                                                | 6.09 us: 1.01x slower                                                  |
| regex_dna                | 204 ms                                                 | 206 ms: 1.01x slower                                                   |
| pycparser                | 1.18 sec                                               | 1.20 sec: 1.01x slower                                                 |
| pathlib                  | 18.2 ms                                                | 18.5 ms: 1.02x slower                                                  |
| bench_thread_pool        | 819 us                                                 | 834 us: 1.02x slower                                                   |
| sqlglot_optimize         | 53.1 ms                                                | 54.3 ms: 1.02x slower                                                  |
| logging_format           | 6.68 us                                                | 6.85 us: 1.02x slower                                                  |
| create_gc_cycles         | 1.49 ms                                                | 1.52 ms: 1.03x slower                                                  |
| scimark_monte_carlo      | 68.1 ms                                                | 69.8 ms: 1.03x slower                                                  |
| comprehensions           | 22.4 us                                                | 23.1 us: 1.03x slower                                                  |
| docutils                 | 2.63 sec                                               | 2.71 sec: 1.03x slower                                                 |
| scimark_sor              | 118 ms                                                 | 123 ms: 1.04x slower                                                   |
| pprint_pformat           | 1.46 sec                                               | 1.52 sec: 1.04x slower                                                 |
| scimark_lu               | 110 ms                                                 | 114 ms: 1.04x slower                                                   |
| logging_silent           | 101 ns                                                 | 105 ns: 1.04x slower                                                   |
| deepcopy                 | 342 us                                                 | 357 us: 1.04x slower                                                   |
| go                       | 140 ms                                                 | 146 ms: 1.05x slower                                                   |
| nbody                    | 93.1 ms                                                | 97.5 ms: 1.05x slower                                                  |
| richards                 | 45.7 ms                                                | 48.0 ms: 1.05x slower                                                  |
| fannkuch                 | 388 ms                                                 | 408 ms: 1.05x slower                                                   |
| regex_compile            | 138 ms                                                 | 145 ms: 1.05x slower                                                   |
| meteor_contest           | 107 ms                                                 | 112 ms: 1.05x slower                                                   |
| deepcopy_memo            | 37.0 us                                                | 39.2 us: 1.06x slower                                                  |
| unpickle                 | 13.7 us                                                | 14.5 us: 1.06x slower                                                  |
| pprint_safe_repr         | 701 ms                                                 | 748 ms: 1.07x slower                                                   |
| regex_v8                 | 22.0 ms                                                | 23.6 ms: 1.07x slower                                                  |
| xml_etree_process        | 53.9 ms                                                | 57.6 ms: 1.07x slower                                                  |
| nqueens                  | 83.4 ms                                                | 89.4 ms: 1.07x slower                                                  |
| float                    | 77.2 ms                                                | 83.1 ms: 1.08x slower                                                  |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.84 ms: 1.08x slower                                                  |
| spectral_norm            | 100 ms                                                 | 108 ms: 1.08x slower                                                   |
| hexiom                   | 6.37 ms                                                | 6.89 ms: 1.08x slower                                                  |
| dulwich_log              | 63.7 ms                                                | 69.0 ms: 1.08x slower                                                  |
| deepcopy_reduce          | 2.94 us                                                | 3.19 us: 1.09x slower                                                  |
| scimark_fft              | 328 ms                                                 | 358 ms: 1.09x slower                                                   |
| mako                     | 10.1 ms                                                | 11.0 ms: 1.09x slower                                                  |
| xml_etree_generate       | 76.2 ms                                                | 83.7 ms: 1.10x slower                                                  |
| pyflate                  | 418 ms                                                 | 461 ms: 1.10x slower                                                   |
| sqlite_synth             | 2.52 us                                                | 2.78 us: 1.10x slower                                                  |
| pickle_list              | 4.11 us                                                | 4.64 us: 1.13x slower                                                  |
| unpack_sequence          | 43.1 ns                                                | 49.0 ns: 1.14x slower                                                  |
| python_startup_no_site   | 6.01 ms                                                | 6.87 ms: 1.14x slower                                                  |
| python_startup           | 8.52 ms                                                | 10.1 ms: 1.18x slower                                                  |
| async_generators         | 368 ms                                                 | 457 ms: 1.24x slower                                                   |
| telco                    | 6.58 ms                                                | 8.22 ms: 1.25x slower                                                  |
| dask                     | 360 ms                                                 | 532 ms: 1.48x slower                                                   |
| Geometric mean           | (ref)                                                  | 1.02x faster                                                           |

Benchmark hidden because not significant (5): sqlglot_normalize, bench_mp_pool, unpickle_list, pickle, json
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 90.02% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
