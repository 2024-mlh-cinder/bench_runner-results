
# Results vs. 3.11.0

- fork: python
- ref: 8b55adfa8ff05477b4be
- machine: linux-x86_64
- commit hash: 8b55adf
- commit date: 2023-09-12
- overall geometric mean: 1.04x faster
- HPT reliability: 90.58%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230912-linux-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.61 sec: 1.01x faster                                                |
| tornado_http   | 96.3 ms                                                | 95.4 ms: 1.01x faster                                                 |
| Geometric mean | (ref)                                                  | 1.01x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230912-linux-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 187 ms: 1.06x faster                                                  |
| nbody          | 93.1 ms                                                | 89.8 ms: 1.04x faster                                                 |
| float          | 77.2 ms                                                | 80.5 ms: 1.04x slower                                                 |
| Geometric mean | (ref)                                                  | 1.02x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230912-linux-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.58 ms: 1.12x faster                                                 |
| regex_compile  | 138 ms                                                 | 135 ms: 1.02x faster                                                  |
| regex_dna      | 204 ms                                                 | 214 ms: 1.05x slower                                                  |
| regex_v8       | 22.0 ms                                                | 24.6 ms: 1.12x slower                                                 |
| Geometric mean | (ref)                                                  | 1.01x slower                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230912-linux-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.86 ms: 1.28x faster                                                 |
| tomli_loads          | 2.22 sec                                               | 2.07 sec: 1.07x faster                                                |
| json_loads           | 26.5 us                                                | 25.3 us: 1.05x faster                                                 |
| xml_etree_parse      | 158 ms                                                 | 152 ms: 1.04x faster                                                  |
| unpickle_pure_python | 228 us                                                 | 221 us: 1.03x faster                                                  |
| unpickle_list        | 4.91 us                                                | 4.82 us: 1.02x faster                                                 |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.01x faster                                                  |
| pickle_pure_python   | 306 us                                                 | 302 us: 1.01x faster                                                  |
| pickle_dict          | 31.1 us                                                | 32.5 us: 1.05x slower                                                 |
| unpickle             | 13.7 us                                                | 14.5 us: 1.06x slower                                                 |
| xml_etree_process    | 53.9 ms                                                | 58.0 ms: 1.08x slower                                                 |
| pickle               | 10.1 us                                                | 10.8 us: 1.08x slower                                                 |
| pickle_list          | 4.11 us                                                | 4.53 us: 1.10x slower                                                 |
| xml_etree_generate   | 76.2 ms                                                | 84.6 ms: 1.11x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.00x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230912-linux-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.85 ms: 1.14x slower                                                 |
| python_startup         | 8.52 ms                                                | 10.1 ms: 1.18x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.16x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230912-linux-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 10.9 ms: 1.08x slower                                                 |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230912-linux-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 146 us: 3.33x faster                                                  |
| generators               | 73.5 ms                                                | 29.1 ms: 2.53x faster                                                 |
| asyncio_tcp              | 922 ms                                                 | 491 ms: 1.88x faster                                                  |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.79 sec: 1.75x faster                                                |
| json_dumps               | 12.6 ms                                                | 9.86 ms: 1.28x faster                                                 |
| mypy2                    | 420 ms                                                 | 339 ms: 1.24x faster                                                  |
| async_tree_none          | 526 ms                                                 | 438 ms: 1.20x faster                                                  |
| coverage                 | 100 ms                                                 | 85.7 ms: 1.17x faster                                                 |
| coroutines               | 25.5 ms                                                | 22.2 ms: 1.15x faster                                                 |
| chaos                    | 69.2 ms                                                | 60.6 ms: 1.14x faster                                                 |
| regex_effbot             | 3.99 ms                                                | 3.58 ms: 1.12x faster                                                 |
| async_tree_memoization   | 627 ms                                                 | 567 ms: 1.11x faster                                                  |
| deltablue                | 3.67 ms                                                | 3.32 ms: 1.11x faster                                                 |
| sqlglot_parse            | 1.40 ms                                                | 1.27 ms: 1.11x faster                                                 |
| comprehensions           | 22.4 us                                                | 20.3 us: 1.10x faster                                                 |
| raytrace                 | 297 ms                                                 | 270 ms: 1.10x faster                                                  |
| async_tree_io            | 1.30 sec                                               | 1.19 sec: 1.09x faster                                                |
| sqlglot_transpile        | 1.70 ms                                                | 1.58 ms: 1.08x faster                                                 |
| tomli_loads              | 2.22 sec                                               | 2.07 sec: 1.07x faster                                                |
| crypto_pyaes             | 74.7 ms                                                | 69.9 ms: 1.07x faster                                                 |
| pidigits                 | 198 ms                                                 | 187 ms: 1.06x faster                                                  |
| hexiom                   | 6.37 ms                                                | 6.03 ms: 1.06x faster                                                 |
| nqueens                  | 83.4 ms                                                | 79.5 ms: 1.05x faster                                                 |
| json_loads               | 26.5 us                                                | 25.3 us: 1.05x faster                                                 |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 709 ms: 1.04x faster                                                  |
| xml_etree_parse          | 158 ms                                                 | 152 ms: 1.04x faster                                                  |
| nbody                    | 93.1 ms                                                | 89.8 ms: 1.04x faster                                                 |
| richards_super           | 56.8 ms                                                | 54.8 ms: 1.04x faster                                                 |
| mdp                      | 2.62 sec                                               | 2.53 sec: 1.03x faster                                                |
| json                     | 4.94 ms                                                | 4.78 ms: 1.03x faster                                                 |
| sqlglot_normalize        | 108 ms                                                 | 104 ms: 1.03x faster                                                  |
| unpickle_pure_python     | 228 us                                                 | 221 us: 1.03x faster                                                  |
| scimark_monte_carlo      | 68.1 ms                                                | 66.4 ms: 1.03x faster                                                 |
| regex_compile            | 138 ms                                                 | 135 ms: 1.02x faster                                                  |
| unpickle_list            | 4.91 us                                                | 4.82 us: 1.02x faster                                                 |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.01x faster                                                  |
| bench_thread_pool        | 819 us                                                 | 809 us: 1.01x faster                                                  |
| pickle_pure_python       | 306 us                                                 | 302 us: 1.01x faster                                                  |
| scimark_lu               | 110 ms                                                 | 109 ms: 1.01x faster                                                  |
| sqlglot_optimize         | 53.1 ms                                                | 52.6 ms: 1.01x faster                                                 |
| logging_simple           | 6.03 us                                                | 5.98 us: 1.01x faster                                                 |
| tornado_http             | 96.3 ms                                                | 95.4 ms: 1.01x faster                                                 |
| logging_format           | 6.68 us                                                | 6.63 us: 1.01x faster                                                 |
| docutils                 | 2.63 sec                                               | 2.61 sec: 1.01x faster                                                |
| deepcopy_memo            | 37.0 us                                                | 36.8 us: 1.01x faster                                                 |
| gc_traversal             | 4.02 ms                                                | 4.00 ms: 1.00x faster                                                 |
| pprint_pformat           | 1.46 sec                                               | 1.46 sec: 1.01x slower                                                |
| deepcopy                 | 342 us                                                 | 345 us: 1.01x slower                                                  |
| fannkuch                 | 388 ms                                                 | 395 ms: 1.02x slower                                                  |
| pprint_safe_repr         | 701 ms                                                 | 721 ms: 1.03x slower                                                  |
| create_gc_cycles         | 1.49 ms                                                | 1.53 ms: 1.03x slower                                                 |
| richards                 | 45.7 ms                                                | 47.6 ms: 1.04x slower                                                 |
| scimark_sor              | 118 ms                                                 | 123 ms: 1.04x slower                                                  |
| float                    | 77.2 ms                                                | 80.5 ms: 1.04x slower                                                 |
| unpack_sequence          | 43.1 ns                                                | 45.0 ns: 1.04x slower                                                 |
| pickle_dict              | 31.1 us                                                | 32.5 us: 1.05x slower                                                 |
| dulwich_log              | 63.7 ms                                                | 66.6 ms: 1.05x slower                                                 |
| regex_dna                | 204 ms                                                 | 214 ms: 1.05x slower                                                  |
| deepcopy_reduce          | 2.94 us                                                | 3.10 us: 1.05x slower                                                 |
| spectral_norm            | 100 ms                                                 | 106 ms: 1.06x slower                                                  |
| unpickle                 | 13.7 us                                                | 14.5 us: 1.06x slower                                                 |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.79 ms: 1.06x slower                                                 |
| scimark_fft              | 328 ms                                                 | 353 ms: 1.08x slower                                                  |
| xml_etree_process        | 53.9 ms                                                | 58.0 ms: 1.08x slower                                                 |
| pickle                   | 10.1 us                                                | 10.8 us: 1.08x slower                                                 |
| mako                     | 10.1 ms                                                | 10.9 ms: 1.08x slower                                                 |
| pyflate                  | 418 ms                                                 | 459 ms: 1.10x slower                                                  |
| sqlite_synth             | 2.52 us                                                | 2.77 us: 1.10x slower                                                 |
| pickle_list              | 4.11 us                                                | 4.53 us: 1.10x slower                                                 |
| xml_etree_generate       | 76.2 ms                                                | 84.6 ms: 1.11x slower                                                 |
| regex_v8                 | 22.0 ms                                                | 24.6 ms: 1.12x slower                                                 |
| python_startup_no_site   | 6.01 ms                                                | 6.85 ms: 1.14x slower                                                 |
| python_startup           | 8.52 ms                                                | 10.1 ms: 1.18x slower                                                 |
| async_generators         | 368 ms                                                 | 443 ms: 1.20x slower                                                  |
| telco                    | 6.58 ms                                                | 8.23 ms: 1.25x slower                                                 |
| dask                     | 360 ms                                                 | 526 ms: 1.46x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.04x faster                                                          |

Benchmark hidden because not significant (6): meteor_contest, go, bench_mp_pool, pathlib, logging_silent, pycparser
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 90.58% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
