
# Results vs. 3.11.0

- fork: python
- ref: v3.11.6
- machine: linux-x86_64
- commit hash: 8b6ee5b
- commit date: 2023-10-02
- overall geometric mean: 1.00x faster
- HPT reliability: 75.63%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-linux-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 259 ms                                                 | 257 ms: 1.01x faster                                   |
| chameleon      | 6.47 ms                                                | 6.61 ms: 1.02x slower                                  |
| docutils       | 2.63 sec                                               | 2.58 sec: 1.02x faster                                 |
| tornado_http   | 96.3 ms                                                | 96.9 ms: 1.01x slower                                  |
| Geometric mean | (ref)                                                  | 1.00x faster                                           |

Benchmark hidden because not significant (1): html5lib

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-linux-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| float          | 77.2 ms                                                | 75.7 ms: 1.02x faster                                  |
| nbody          | 93.1 ms                                                | 92.6 ms: 1.01x faster                                  |
| pidigits       | 198 ms                                                 | 199 ms: 1.01x slower                                   |
| Geometric mean | (ref)                                                  | 1.01x faster                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-linux-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.47 ms: 1.15x faster                                  |
| regex_dna      | 204 ms                                                 | 199 ms: 1.03x faster                                   |
| regex_compile  | 138 ms                                                 | 136 ms: 1.02x faster                                   |
| regex_v8       | 22.0 ms                                                | 21.9 ms: 1.00x faster                                  |
| Geometric mean | (ref)                                                  | 1.05x faster                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-linux-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| json_loads           | 26.5 us                                                | 23.9 us: 1.11x faster                                  |
| pickle_dict          | 31.1 us                                                | 29.9 us: 1.04x faster                                  |
| unpickle             | 13.7 us                                                | 13.3 us: 1.03x faster                                  |
| pickle               | 10.1 us                                                | 9.82 us: 1.03x faster                                  |
| pickle_list          | 4.11 us                                                | 4.05 us: 1.01x faster                                  |
| xml_etree_iterparse  | 104 ms                                                 | 103 ms: 1.01x faster                                   |
| xml_etree_generate   | 76.2 ms                                                | 76.7 ms: 1.01x slower                                  |
| unpickle_pure_python | 228 us                                                 | 230 us: 1.01x slower                                   |
| json_dumps           | 12.6 ms                                                | 12.7 ms: 1.01x slower                                  |
| tomli_loads          | 2.22 sec                                               | 2.25 sec: 1.01x slower                                 |
| unpickle_list        | 4.91 us                                                | 5.08 us: 1.04x slower                                  |
| Geometric mean       | (ref)                                                  | 1.01x faster                                           |

Benchmark hidden because not significant (3): xml_etree_parse, xml_etree_process, pickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-linux-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup         | 8.52 ms                                                | 8.50 ms: 1.00x faster                                  |
| python_startup_no_site | 6.01 ms                                                | 6.00 ms: 1.00x faster                                  |
| Geometric mean         | (ref)                                                  | 1.00x faster                                           |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-linux-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|-----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako            | 10.1 ms                                                | 9.88 ms: 1.02x faster                                  |
| django_template | 32.6 ms                                                | 33.1 ms: 1.01x slower                                  |
| genshi_text     | 21.6 ms                                                | 21.9 ms: 1.02x slower                                  |
| Geometric mean  | (ref)                                                  | 1.00x slower                                           |

Benchmark hidden because not significant (1): genshi_xml

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-linux-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_effbot             | 3.99 ms                                                | 3.47 ms: 1.15x faster                                  |
| json_loads               | 26.5 us                                                | 23.9 us: 1.11x faster                                  |
| json                     | 4.94 ms                                                | 4.59 ms: 1.08x faster                                  |
| pycparser                | 1.18 sec                                               | 1.12 sec: 1.06x faster                                 |
| pickle_dict              | 31.1 us                                                | 29.9 us: 1.04x faster                                  |
| async_generators         | 368 ms                                                 | 356 ms: 1.04x faster                                   |
| regex_dna                | 204 ms                                                 | 199 ms: 1.03x faster                                   |
| unpickle                 | 13.7 us                                                | 13.3 us: 1.03x faster                                  |
| pickle                   | 10.1 us                                                | 9.82 us: 1.03x faster                                  |
| logging_format           | 6.68 us                                                | 6.52 us: 1.02x faster                                  |
| mako                     | 10.1 ms                                                | 9.88 ms: 1.02x faster                                  |
| float                    | 77.2 ms                                                | 75.7 ms: 1.02x faster                                  |
| deepcopy_memo            | 37.0 us                                                | 36.3 us: 1.02x faster                                  |
| sqlglot_parse            | 1.40 ms                                                | 1.37 ms: 1.02x faster                                  |
| docutils                 | 2.63 sec                                               | 2.58 sec: 1.02x faster                                 |
| logging_simple           | 6.03 us                                                | 5.93 us: 1.02x faster                                  |
| generators               | 73.5 ms                                                | 72.2 ms: 1.02x faster                                  |
| regex_compile            | 138 ms                                                 | 136 ms: 1.02x faster                                   |
| pyflate                  | 418 ms                                                 | 412 ms: 1.02x faster                                   |
| pickle_list              | 4.11 us                                                | 4.05 us: 1.01x faster                                  |
| meteor_contest           | 107 ms                                                 | 105 ms: 1.01x faster                                   |
| sqlglot_transpile        | 1.70 ms                                                | 1.68 ms: 1.01x faster                                  |
| comprehensions           | 22.4 us                                                | 22.2 us: 1.01x faster                                  |
| sqlalchemy_imperative    | 17.9 ms                                                | 17.7 ms: 1.01x faster                                  |
| raytrace                 | 297 ms                                                 | 293 ms: 1.01x faster                                   |
| flaskblogging            | 7.12 ms                                                | 7.04 ms: 1.01x faster                                  |
| sympy_str                | 290 ms                                                 | 287 ms: 1.01x faster                                   |
| 2to3                     | 259 ms                                                 | 257 ms: 1.01x faster                                   |
| create_gc_cycles         | 1.49 ms                                                | 1.47 ms: 1.01x faster                                  |
| sympy_integrate          | 21.0 ms                                                | 20.8 ms: 1.01x faster                                  |
| sympy_expand             | 475 ms                                                 | 471 ms: 1.01x faster                                   |
| sqlite_synth             | 2.52 us                                                | 2.50 us: 1.01x faster                                  |
| async_tree_none          | 526 ms                                                 | 522 ms: 1.01x faster                                   |
| sympy_sum                | 167 ms                                                 | 165 ms: 1.01x faster                                   |
| nbody                    | 93.1 ms                                                | 92.6 ms: 1.01x faster                                  |
| chaos                    | 69.2 ms                                                | 68.8 ms: 1.01x faster                                  |
| xml_etree_iterparse      | 104 ms                                                 | 103 ms: 1.01x faster                                   |
| regex_v8                 | 22.0 ms                                                | 21.9 ms: 1.00x faster                                  |
| pprint_pformat           | 1.46 sec                                               | 1.45 sec: 1.00x faster                                 |
| crypto_pyaes             | 74.7 ms                                                | 74.4 ms: 1.00x faster                                  |
| python_startup           | 8.52 ms                                                | 8.50 ms: 1.00x faster                                  |
| aiohttp                  | 1.10 ms                                                | 1.10 ms: 1.00x faster                                  |
| sqlglot_optimize         | 53.1 ms                                                | 53.0 ms: 1.00x faster                                  |
| python_startup_no_site   | 6.01 ms                                                | 6.00 ms: 1.00x faster                                  |
| asyncio_tcp_ssl          | 3.14 sec                                               | 3.14 sec: 1.00x slower                                 |
| bench_thread_pool        | 819 us                                                 | 821 us: 1.00x slower                                   |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 742 ms: 1.00x slower                                   |
| xml_etree_generate       | 76.2 ms                                                | 76.7 ms: 1.01x slower                                  |
| unpickle_pure_python     | 228 us                                                 | 230 us: 1.01x slower                                   |
| pidigits                 | 198 ms                                                 | 199 ms: 1.01x slower                                   |
| tornado_http             | 96.3 ms                                                | 96.9 ms: 1.01x slower                                  |
| async_tree_memoization   | 627 ms                                                 | 632 ms: 1.01x slower                                   |
| json_dumps               | 12.6 ms                                                | 12.7 ms: 1.01x slower                                  |
| scimark_fft              | 328 ms                                                 | 332 ms: 1.01x slower                                   |
| telco                    | 6.58 ms                                                | 6.66 ms: 1.01x slower                                  |
| dulwich_log              | 63.7 ms                                                | 64.5 ms: 1.01x slower                                  |
| asyncio_tcp              | 922 ms                                                 | 934 ms: 1.01x slower                                   |
| django_template          | 32.6 ms                                                | 33.1 ms: 1.01x slower                                  |
| deepcopy_reduce          | 2.94 us                                                | 2.98 us: 1.01x slower                                  |
| typing_runtime_protocols | 486 us                                                 | 493 us: 1.01x slower                                   |
| tomli_loads              | 2.22 sec                                               | 2.25 sec: 1.01x slower                                 |
| coroutines               | 25.5 ms                                                | 25.9 ms: 1.02x slower                                  |
| genshi_text              | 21.6 ms                                                | 21.9 ms: 1.02x slower                                  |
| hexiom                   | 6.37 ms                                                | 6.49 ms: 1.02x slower                                  |
| chameleon                | 6.47 ms                                                | 6.61 ms: 1.02x slower                                  |
| spectral_norm            | 100 ms                                                 | 103 ms: 1.03x slower                                   |
| unpickle_list            | 4.91 us                                                | 5.08 us: 1.04x slower                                  |
| richards_super           | 56.8 ms                                                | 59.0 ms: 1.04x slower                                  |
| richards                 | 45.7 ms                                                | 47.9 ms: 1.05x slower                                  |
| gc_traversal             | 4.02 ms                                                | 4.25 ms: 1.06x slower                                  |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.76 ms: 1.06x slower                                  |
| deltablue                | 3.67 ms                                                | 3.94 ms: 1.07x slower                                  |
| mdp                      | 2.62 sec                                               | 2.81 sec: 1.08x slower                                 |
| mypy2                    | 420 ms                                                 | 529 ms: 1.26x slower                                   |
| Geometric mean           | (ref)                                                  | 1.00x faster                                           |

Benchmark hidden because not significant (25): html5lib, unpack_sequence, genshi_xml, gunicorn, dask, xml_etree_parse, scimark_sor, pathlib, fannkuch, xml_etree_process, go, scimark_lu, bench_mp_pool, deepcopy, sqlglot_normalize, thrift, pickle_pure_python, pprint_safe_repr, logging_silent, sqlalchemy_declarative, nqueens, async_tree_io, djangocms, scimark_monte_carlo, pylint
Ignored benchmarks (1) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: coverage


# HPT report

- Reliability score: 75.63% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
