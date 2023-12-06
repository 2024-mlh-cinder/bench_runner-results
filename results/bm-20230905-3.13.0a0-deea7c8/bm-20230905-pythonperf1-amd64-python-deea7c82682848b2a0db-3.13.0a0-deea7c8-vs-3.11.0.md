
# Results vs. 3.11.0

- fork: python
- ref: deea7c82682848b2a0db
- machine: windows-amd64
- commit hash: deea7c8
- commit date: 2023-09-05
- overall geometric mean: 1.02x faster
- HPT reliability: 86.08%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| docutils       | 1.60 sec                                                    | 1.65 sec: 1.03x slower                                                     |
| Geometric mean | (ref)                                                       | 1.01x slower                                                               |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pidigits       | 148 ms                                                      | 150 ms: 1.01x slower                                                       |
| float          | 54.6 ms                                                     | 56.7 ms: 1.04x slower                                                      |
| nbody          | 70.0 ms                                                     | 78.2 ms: 1.12x slower                                                      |
| Geometric mean | (ref)                                                       | 1.06x slower                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_dna      | 115 ms                                                      | 119 ms: 1.03x slower                                                       |
| regex_compile  | 90.6 ms                                                     | 94.3 ms: 1.04x slower                                                      |
| regex_effbot   | 1.50 ms                                                     | 1.58 ms: 1.06x slower                                                      |
| regex_v8       | 13.8 ms                                                     | 14.8 ms: 1.07x slower                                                      |
| Geometric mean | (ref)                                                       | 1.05x slower                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| json_dumps           | 7.56 ms                                                     | 5.85 ms: 1.29x faster                                                      |
| unpickle_pure_python | 152 us                                                      | 140 us: 1.08x faster                                                       |
| xml_etree_parse      | 95.9 ms                                                     | 91.2 ms: 1.05x faster                                                      |
| pickle_pure_python   | 200 us                                                      | 197 us: 1.01x faster                                                       |
| pickle_dict          | 18.5 us                                                     | 18.9 us: 1.02x slower                                                      |
| unpickle             | 8.09 us                                                     | 8.39 us: 1.04x slower                                                      |
| json_loads           | 12.9 us                                                     | 13.5 us: 1.05x slower                                                      |
| unpickle_list        | 2.55 us                                                     | 2.69 us: 1.06x slower                                                      |
| xml_etree_process    | 37.1 ms                                                     | 39.2 ms: 1.06x slower                                                      |
| pickle_list          | 2.68 us                                                     | 2.85 us: 1.06x slower                                                      |
| xml_etree_generate   | 52.2 ms                                                     | 56.0 ms: 1.07x slower                                                      |
| pickle               | 6.61 us                                                     | 7.09 us: 1.07x slower                                                      |
| tomli_loads          | 1.41 sec                                                    | 1.57 sec: 1.11x slower                                                     |
| Geometric mean       | (ref)                                                       | 1.01x slower                                                               |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 16.5 ms: 1.04x slower                                                      |
| python_startup         | 18.7 ms                                                     | 19.7 ms: 1.05x slower                                                      |
| Geometric mean         | (ref)                                                       | 1.05x slower                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|-----------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako      | 7.26 ms                                                     | 7.47 ms: 1.03x slower                                                      |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|--------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| typing_runtime_protocols | 322 us                                                      | 98.3 us: 3.27x faster                                                      |
| asyncio_tcp              | 699 ms                                                      | 486 ms: 1.44x faster                                                       |
| generators               | 33.8 ms                                                     | 24.2 ms: 1.40x faster                                                      |
| json_dumps               | 7.56 ms                                                     | 5.85 ms: 1.29x faster                                                      |
| unpack_sequence          | 46.1 ns                                                     | 37.6 ns: 1.23x faster                                                      |
| coverage                 | 55.9 ms                                                     | 47.1 ms: 1.19x faster                                                      |
| raytrace                 | 211 ms                                                      | 181 ms: 1.16x faster                                                       |
| async_tree_none          | 320 ms                                                      | 282 ms: 1.14x faster                                                       |
| deltablue                | 2.61 ms                                                     | 2.30 ms: 1.13x faster                                                      |
| richards_super           | 37.5 ms                                                     | 33.1 ms: 1.13x faster                                                      |
| asyncio_tcp_ssl          | 2.11 sec                                                    | 1.88 sec: 1.12x faster                                                     |
| sqlglot_parse            | 952 us                                                      | 870 us: 1.09x faster                                                       |
| logging_silent           | 69.8 ns                                                     | 64.2 ns: 1.09x faster                                                      |
| json                     | 3.25 ms                                                     | 3.00 ms: 1.09x faster                                                      |
| unpickle_pure_python     | 152 us                                                      | 140 us: 1.08x faster                                                       |
| mdp                      | 1.67 sec                                                    | 1.54 sec: 1.08x faster                                                     |
| comprehensions           | 15.9 us                                                     | 14.8 us: 1.08x faster                                                      |
| chaos                    | 47.1 ms                                                     | 43.7 ms: 1.08x faster                                                      |
| scimark_lu               | 63.5 ms                                                     | 59.4 ms: 1.07x faster                                                      |
| sqlglot_transpile        | 1.16 ms                                                     | 1.10 ms: 1.06x faster                                                      |
| scimark_sparse_mat_mult  | 2.57 ms                                                     | 2.44 ms: 1.05x faster                                                      |
| xml_etree_parse          | 95.9 ms                                                     | 91.2 ms: 1.05x faster                                                      |
| hexiom                   | 4.55 ms                                                     | 4.34 ms: 1.05x faster                                                      |
| crypto_pyaes             | 47.6 ms                                                     | 45.5 ms: 1.04x faster                                                      |
| nqueens                  | 64.9 ms                                                     | 62.2 ms: 1.04x faster                                                      |
| richards                 | 30.6 ms                                                     | 29.4 ms: 1.04x faster                                                      |
| async_tree_io            | 779 ms                                                      | 752 ms: 1.04x faster                                                       |
| scimark_monte_carlo      | 44.6 ms                                                     | 43.3 ms: 1.03x faster                                                      |
| mypy2                    | 229 ms                                                      | 222 ms: 1.03x faster                                                       |
| async_tree_cpu_io_mixed  | 501 ms                                                      | 487 ms: 1.03x faster                                                       |
| async_tree_memoization   | 371 ms                                                      | 361 ms: 1.03x faster                                                       |
| pickle_pure_python       | 200 us                                                      | 197 us: 1.01x faster                                                       |
| deepcopy_memo            | 25.2 us                                                     | 24.9 us: 1.01x faster                                                      |
| meteor_contest           | 74.7 ms                                                     | 75.1 ms: 1.01x slower                                                      |
| go                       | 97.3 ms                                                     | 97.9 ms: 1.01x slower                                                      |
| deepcopy                 | 246 us                                                      | 248 us: 1.01x slower                                                       |
| pidigits                 | 148 ms                                                      | 150 ms: 1.01x slower                                                       |
| logging_simple           | 6.61 us                                                     | 6.70 us: 1.01x slower                                                      |
| fannkuch                 | 252 ms                                                      | 255 ms: 1.01x slower                                                       |
| gc_traversal             | 1.46 ms                                                     | 1.48 ms: 1.01x slower                                                      |
| sqlglot_normalize        | 190 ms                                                      | 194 ms: 1.02x slower                                                       |
| pickle_dict              | 18.5 us                                                     | 18.9 us: 1.02x slower                                                      |
| logging_format           | 7.01 us                                                     | 7.19 us: 1.02x slower                                                      |
| pyflate                  | 304 ms                                                      | 312 ms: 1.03x slower                                                       |
| mako                     | 7.26 ms                                                     | 7.47 ms: 1.03x slower                                                      |
| docutils                 | 1.60 sec                                                    | 1.65 sec: 1.03x slower                                                     |
| regex_dna                | 115 ms                                                      | 119 ms: 1.03x slower                                                       |
| unpickle                 | 8.09 us                                                     | 8.39 us: 1.04x slower                                                      |
| sqlglot_optimize         | 34.9 ms                                                     | 36.2 ms: 1.04x slower                                                      |
| float                    | 54.6 ms                                                     | 56.7 ms: 1.04x slower                                                      |
| regex_compile            | 90.6 ms                                                     | 94.3 ms: 1.04x slower                                                      |
| python_startup_no_site   | 15.9 ms                                                     | 16.5 ms: 1.04x slower                                                      |
| sqlite_synth             | 1.68 us                                                     | 1.76 us: 1.04x slower                                                      |
| create_gc_cycles         | 693 us                                                      | 723 us: 1.04x slower                                                       |
| dulwich_log              | 44.5 ms                                                     | 46.5 ms: 1.04x slower                                                      |
| spectral_norm            | 67.9 ms                                                     | 71.2 ms: 1.05x slower                                                      |
| scimark_fft              | 178 ms                                                      | 187 ms: 1.05x slower                                                       |
| json_loads               | 12.9 us                                                     | 13.5 us: 1.05x slower                                                      |
| pprint_safe_repr         | 512 ms                                                      | 538 ms: 1.05x slower                                                       |
| python_startup           | 18.7 ms                                                     | 19.7 ms: 1.05x slower                                                      |
| unpickle_list            | 2.55 us                                                     | 2.69 us: 1.06x slower                                                      |
| regex_effbot             | 1.50 ms                                                     | 1.58 ms: 1.06x slower                                                      |
| xml_etree_process        | 37.1 ms                                                     | 39.2 ms: 1.06x slower                                                      |
| pprint_pformat           | 1.04 sec                                                    | 1.10 sec: 1.06x slower                                                     |
| pickle_list              | 2.68 us                                                     | 2.85 us: 1.06x slower                                                      |
| regex_v8                 | 13.8 ms                                                     | 14.8 ms: 1.07x slower                                                      |
| xml_etree_generate       | 52.2 ms                                                     | 56.0 ms: 1.07x slower                                                      |
| pickle                   | 6.61 us                                                     | 7.09 us: 1.07x slower                                                      |
| bench_mp_pool            | 62.5 ms                                                     | 67.3 ms: 1.08x slower                                                      |
| pycparser                | 691 ms                                                      | 748 ms: 1.08x slower                                                       |
| deepcopy_reduce          | 2.07 us                                                     | 2.26 us: 1.09x slower                                                      |
| tomli_loads              | 1.41 sec                                                    | 1.57 sec: 1.11x slower                                                     |
| pathlib                  | 71.4 ms                                                     | 79.5 ms: 1.11x slower                                                      |
| nbody                    | 70.0 ms                                                     | 78.2 ms: 1.12x slower                                                      |
| telco                    | 3.90 ms                                                     | 4.60 ms: 1.18x slower                                                      |
| scimark_sor              | 75.6 ms                                                     | 89.4 ms: 1.18x slower                                                      |
| async_generators         | 178 ms                                                      | 243 ms: 1.37x slower                                                       |
| dask                     | 264 ms                                                      | 394 ms: 1.49x slower                                                       |
| Geometric mean           | (ref)                                                       | 1.02x faster                                                               |

Benchmark hidden because not significant (4): tornado_http, bench_thread_pool, coroutines, xml_etree_iterparse
Ignored benchmarks (16) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 86.08% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
