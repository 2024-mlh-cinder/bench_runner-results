
# Results vs. 3.11.0

- fork: python
- ref: v3.11.5
- machine: linux-x86_64
- commit hash: cce6ba9
- commit date: 2023-08-24
- overall geometric mean: 1.00x faster
- HPT reliability: 58.29%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230824-linux-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| chameleon      | 6.47 ms                                                | 6.61 ms: 1.02x slower                                  |
| docutils       | 2.63 sec                                               | 2.59 sec: 1.01x faster                                 |
| Geometric mean | (ref)                                                  | 1.00x slower                                           |

Benchmark hidden because not significant (3): 2to3, html5lib, tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230824-linux-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 190 ms: 1.04x faster                                   |
| nbody          | 93.1 ms                                                | 95.6 ms: 1.03x slower                                  |
| Geometric mean | (ref)                                                  | 1.01x faster                                           |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230824-linux-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.25 ms: 1.23x faster                                  |
| regex_dna      | 204 ms                                                 | 201 ms: 1.02x faster                                   |
| regex_v8       | 22.0 ms                                                | 21.8 ms: 1.01x faster                                  |
| regex_compile  | 138 ms                                                 | 136 ms: 1.01x faster                                   |
| Geometric mean | (ref)                                                  | 1.06x faster                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230824-linux-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| unpickle             | 13.7 us                                                | 13.3 us: 1.03x faster                                  |
| json_loads           | 26.5 us                                                | 25.9 us: 1.02x faster                                  |
| pickle_dict          | 31.1 us                                                | 31.0 us: 1.00x faster                                  |
| unpickle_pure_python | 228 us                                                 | 229 us: 1.00x slower                                   |
| xml_etree_iterparse  | 104 ms                                                 | 105 ms: 1.01x slower                                   |
| unpickle_list        | 4.91 us                                                | 5.00 us: 1.02x slower                                  |
| Geometric mean       | (ref)                                                  | 1.00x faster                                           |

Benchmark hidden because not significant (8): pickle, xml_etree_process, xml_etree_generate, pickle_pure_python, pickle_list, xml_etree_parse, tomli_loads, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230824-linux-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup         | 8.52 ms                                                | 8.56 ms: 1.00x slower                                  |
| python_startup_no_site | 6.01 ms                                                | 6.04 ms: 1.00x slower                                  |
| Geometric mean         | (ref)                                                  | 1.00x slower                                           |

Benchmarks with tag 'template':
===============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230824-linux-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako           | 10.1 ms                                                | 9.99 ms: 1.01x faster                                  |
| genshi_xml     | 51.8 ms                                                | 52.8 ms: 1.02x slower                                  |
| genshi_text    | 21.6 ms                                                | 22.3 ms: 1.03x slower                                  |
| Geometric mean | (ref)                                                  | 1.01x slower                                           |

Benchmark hidden because not significant (1): django_template

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230824-linux-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_effbot             | 3.99 ms                                                | 3.25 ms: 1.23x faster                                  |
| gc_traversal             | 4.02 ms                                                | 3.64 ms: 1.11x faster                                  |
| asyncio_tcp              | 922 ms                                                 | 864 ms: 1.07x faster                                   |
| pidigits                 | 198 ms                                                 | 190 ms: 1.04x faster                                   |
| pycparser                | 1.18 sec                                               | 1.13 sec: 1.04x faster                                 |
| unpickle                 | 13.7 us                                                | 13.3 us: 1.03x faster                                  |
| logging_silent           | 101 ns                                                 | 98.6 ns: 1.03x faster                                  |
| json                     | 4.94 ms                                                | 4.83 ms: 1.02x faster                                  |
| scimark_lu               | 110 ms                                                 | 107 ms: 1.02x faster                                   |
| json_loads               | 26.5 us                                                | 25.9 us: 1.02x faster                                  |
| async_generators         | 368 ms                                                 | 361 ms: 1.02x faster                                   |
| logging_format           | 6.68 us                                                | 6.55 us: 1.02x faster                                  |
| sqlglot_parse            | 1.40 ms                                                | 1.37 ms: 1.02x faster                                  |
| logging_simple           | 6.03 us                                                | 5.93 us: 1.02x faster                                  |
| sqlglot_transpile        | 1.70 ms                                                | 1.67 ms: 1.02x faster                                  |
| meteor_contest           | 107 ms                                                 | 105 ms: 1.02x faster                                   |
| regex_dna                | 204 ms                                                 | 201 ms: 1.02x faster                                   |
| docutils                 | 2.63 sec                                               | 2.59 sec: 1.01x faster                                 |
| regex_v8                 | 22.0 ms                                                | 21.8 ms: 1.01x faster                                  |
| fannkuch                 | 388 ms                                                 | 383 ms: 1.01x faster                                   |
| regex_compile            | 138 ms                                                 | 136 ms: 1.01x faster                                   |
| crypto_pyaes             | 74.7 ms                                                | 73.9 ms: 1.01x faster                                  |
| mdp                      | 2.62 sec                                               | 2.59 sec: 1.01x faster                                 |
| mako                     | 10.1 ms                                                | 9.99 ms: 1.01x faster                                  |
| chaos                    | 69.2 ms                                                | 68.5 ms: 1.01x faster                                  |
| pathlib                  | 18.2 ms                                                | 18.1 ms: 1.01x faster                                  |
| raytrace                 | 297 ms                                                 | 295 ms: 1.00x faster                                   |
| pprint_pformat           | 1.46 sec                                               | 1.45 sec: 1.00x faster                                 |
| pickle_dict              | 31.1 us                                                | 31.0 us: 1.00x faster                                  |
| hexiom                   | 6.37 ms                                                | 6.39 ms: 1.00x slower                                  |
| unpickle_pure_python     | 228 us                                                 | 229 us: 1.00x slower                                   |
| sympy_integrate          | 21.0 ms                                                | 21.1 ms: 1.00x slower                                  |
| generators               | 73.5 ms                                                | 73.8 ms: 1.00x slower                                  |
| python_startup           | 8.52 ms                                                | 8.56 ms: 1.00x slower                                  |
| sympy_sum                | 167 ms                                                 | 167 ms: 1.00x slower                                   |
| deltablue                | 3.67 ms                                                | 3.69 ms: 1.00x slower                                  |
| python_startup_no_site   | 6.01 ms                                                | 6.04 ms: 1.00x slower                                  |
| go                       | 140 ms                                                 | 141 ms: 1.01x slower                                   |
| sqlglot_normalize        | 108 ms                                                 | 108 ms: 1.01x slower                                   |
| deepcopy_memo            | 37.0 us                                                | 37.2 us: 1.01x slower                                  |
| thrift                   | 756 us                                                 | 763 us: 1.01x slower                                   |
| nqueens                  | 83.4 ms                                                | 84.2 ms: 1.01x slower                                  |
| comprehensions           | 22.4 us                                                | 22.7 us: 1.01x slower                                  |
| scimark_monte_carlo      | 68.1 ms                                                | 68.8 ms: 1.01x slower                                  |
| sqlalchemy_declarative   | 138 ms                                                 | 140 ms: 1.01x slower                                   |
| xml_etree_iterparse      | 104 ms                                                 | 105 ms: 1.01x slower                                   |
| gunicorn                 | 1.18 ms                                                | 1.19 ms: 1.01x slower                                  |
| asyncio_tcp_ssl          | 3.14 sec                                               | 3.18 sec: 1.01x slower                                 |
| typing_runtime_protocols | 486 us                                                 | 493 us: 1.01x slower                                   |
| deepcopy_reduce          | 2.94 us                                                | 2.99 us: 1.02x slower                                  |
| unpack_sequence          | 43.1 ns                                                | 43.9 ns: 1.02x slower                                  |
| unpickle_list            | 4.91 us                                                | 5.00 us: 1.02x slower                                  |
| genshi_xml               | 51.8 ms                                                | 52.8 ms: 1.02x slower                                  |
| async_tree_memoization   | 627 ms                                                 | 641 ms: 1.02x slower                                   |
| chameleon                | 6.47 ms                                                | 6.61 ms: 1.02x slower                                  |
| nbody                    | 93.1 ms                                                | 95.6 ms: 1.03x slower                                  |
| deepcopy                 | 342 us                                                 | 351 us: 1.03x slower                                   |
| richards_super           | 56.8 ms                                                | 58.3 ms: 1.03x slower                                  |
| richards                 | 45.7 ms                                                | 47.1 ms: 1.03x slower                                  |
| genshi_text              | 21.6 ms                                                | 22.3 ms: 1.03x slower                                  |
| spectral_norm            | 100 ms                                                 | 104 ms: 1.04x slower                                   |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.72 ms: 1.05x slower                                  |
| mypy2                    | 420 ms                                                 | 532 ms: 1.27x slower                                   |
| Geometric mean           | (ref)                                                  | 1.00x faster                                           |

Benchmark hidden because not significant (36): pylint, scimark_sor, html5lib, pickle, coroutines, float, sqlalchemy_imperative, pprint_safe_repr, bench_thread_pool, sqlglot_optimize, create_gc_cycles, async_tree_none, xml_etree_process, 2to3, bench_mp_pool, django_template, sqlite_synth, xml_etree_generate, pickle_pure_python, pyflate, dask, async_tree_cpu_io_mixed, pickle_list, xml_etree_parse, tomli_loads, scimark_fft, json_dumps, sympy_str, aiohttp, dulwich_log, sympy_expand, telco, flaskblogging, tornado_http, async_tree_io, djangocms
Ignored benchmarks (1) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: coverage


# HPT report

- Reliability score: 58.29% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
