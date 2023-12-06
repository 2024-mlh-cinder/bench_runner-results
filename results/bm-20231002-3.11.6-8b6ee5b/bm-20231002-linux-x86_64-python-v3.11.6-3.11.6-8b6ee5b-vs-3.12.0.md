
# Results vs. 3.12.0

- fork: python
- ref: v3.11.6
- machine: linux-x86_64
- commit hash: 8b6ee5b
- commit date: 2023-10-02
- overall geometric mean: 1.04x slower
- HPT reliability: 78.64%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-linux-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 268 ms                                                 | 257 ms: 1.04x faster                                   |
| docutils       | 2.70 sec                                               | 2.58 sec: 1.05x faster                                 |
| tornado_http   | 99.6 ms                                                | 96.9 ms: 1.03x faster                                  |
| Geometric mean | (ref)                                                  | 1.04x faster                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-linux-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| float          | 80.7 ms                                                | 75.7 ms: 1.07x faster                                  |
| nbody          | 88.8 ms                                                | 92.6 ms: 1.04x slower                                  |
| pidigits       | 187 ms                                                 | 199 ms: 1.07x slower                                   |
| Geometric mean | (ref)                                                  | 1.01x slower                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-linux-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 136 ms: 1.06x faster                                   |
| regex_dna      | 209 ms                                                 | 199 ms: 1.05x faster                                   |
| regex_effbot   | 3.55 ms                                                | 3.47 ms: 1.02x faster                                  |
| regex_v8       | 22.3 ms                                                | 21.9 ms: 1.02x faster                                  |
| Geometric mean | (ref)                                                  | 1.04x faster                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-linux-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pickle_list          | 4.62 us                                                | 4.05 us: 1.14x faster                                  |
| unpickle             | 15.0 us                                                | 13.3 us: 1.13x faster                                  |
| xml_etree_generate   | 84.8 ms                                                | 76.7 ms: 1.11x faster                                  |
| xml_etree_process    | 58.6 ms                                                | 53.7 ms: 1.09x faster                                  |
| pickle               | 10.6 us                                                | 9.82 us: 1.08x faster                                  |
| json_loads           | 25.2 us                                                | 23.9 us: 1.06x faster                                  |
| pickle_dict          | 31.6 us                                                | 29.9 us: 1.06x faster                                  |
| pickle_pure_python   | 309 us                                                 | 306 us: 1.01x faster                                   |
| tomli_loads          | 2.22 sec                                               | 2.25 sec: 1.02x slower                                 |
| unpickle_list        | 4.95 us                                                | 5.08 us: 1.03x slower                                  |
| xml_etree_parse      | 154 ms                                                 | 158 ms: 1.03x slower                                   |
| unpickle_pure_python | 218 us                                                 | 230 us: 1.05x slower                                   |
| json_dumps           | 9.85 ms                                                | 12.7 ms: 1.29x slower                                  |
| Geometric mean       | (ref)                                                  | 1.02x faster                                           |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-linux-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.00 ms: 1.15x faster                                  |
| python_startup         | 9.47 ms                                                | 8.50 ms: 1.11x faster                                  |
| Geometric mean         | (ref)                                                  | 1.13x faster                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-linux-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|-----------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako      | 10.7 ms                                                | 9.88 ms: 1.08x faster                                  |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-linux-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_generators         | 440 ms                                                 | 356 ms: 1.24x faster                                   |
| python_startup_no_site   | 6.90 ms                                                | 6.00 ms: 1.15x faster                                  |
| pickle_list              | 4.62 us                                                | 4.05 us: 1.14x faster                                  |
| unpickle                 | 15.0 us                                                | 13.3 us: 1.13x faster                                  |
| python_startup           | 9.47 ms                                                | 8.50 ms: 1.11x faster                                  |
| xml_etree_generate       | 84.8 ms                                                | 76.7 ms: 1.11x faster                                  |
| sqlite_synth             | 2.76 us                                                | 2.50 us: 1.10x faster                                  |
| pyflate                  | 450 ms                                                 | 412 ms: 1.09x faster                                   |
| xml_etree_process        | 58.6 ms                                                | 53.7 ms: 1.09x faster                                  |
| mako                     | 10.7 ms                                                | 9.88 ms: 1.08x faster                                  |
| scimark_fft              | 358 ms                                                 | 332 ms: 1.08x faster                                   |
| pickle                   | 10.6 us                                                | 9.82 us: 1.08x faster                                  |
| float                    | 80.7 ms                                                | 75.7 ms: 1.07x faster                                  |
| regex_compile            | 144 ms                                                 | 136 ms: 1.06x faster                                   |
| logging_format           | 6.90 us                                                | 6.52 us: 1.06x faster                                  |
| scimark_sor              | 125 ms                                                 | 118 ms: 1.06x faster                                   |
| json_loads               | 25.2 us                                                | 23.9 us: 1.06x faster                                  |
| pickle_dict              | 31.6 us                                                | 29.9 us: 1.06x faster                                  |
| dulwich_log              | 67.9 ms                                                | 64.5 ms: 1.05x faster                                  |
| deepcopy_reduce          | 3.14 us                                                | 2.98 us: 1.05x faster                                  |
| regex_dna                | 209 ms                                                 | 199 ms: 1.05x faster                                   |
| docutils                 | 2.70 sec                                               | 2.58 sec: 1.05x faster                                 |
| pprint_safe_repr         | 735 ms                                                 | 703 ms: 1.05x faster                                   |
| unpack_sequence          | 44.8 ns                                                | 42.9 ns: 1.04x faster                                  |
| sqlalchemy_imperative    | 18.4 ms                                                | 17.7 ms: 1.04x faster                                  |
| 2to3                     | 268 ms                                                 | 257 ms: 1.04x faster                                   |
| logging_simple           | 6.18 us                                                | 5.93 us: 1.04x faster                                  |
| scimark_lu               | 114 ms                                                 | 110 ms: 1.04x faster                                   |
| deepcopy                 | 355 us                                                 | 342 us: 1.04x faster                                   |
| sqlalchemy_declarative   | 144 ms                                                 | 139 ms: 1.04x faster                                   |
| json                     | 4.77 ms                                                | 4.59 ms: 1.04x faster                                  |
| crypto_pyaes             | 77.2 ms                                                | 74.4 ms: 1.04x faster                                  |
| scimark_monte_carlo      | 71.0 ms                                                | 68.5 ms: 1.04x faster                                  |
| pprint_pformat           | 1.50 sec                                               | 1.45 sec: 1.03x faster                                 |
| telco                    | 6.87 ms                                                | 6.66 ms: 1.03x faster                                  |
| create_gc_cycles         | 1.52 ms                                                | 1.47 ms: 1.03x faster                                  |
| deepcopy_memo            | 37.4 us                                                | 36.3 us: 1.03x faster                                  |
| pycparser                | 1.15 sec                                               | 1.12 sec: 1.03x faster                                 |
| spectral_norm            | 106 ms                                                 | 103 ms: 1.03x faster                                   |
| tornado_http             | 99.6 ms                                                | 96.9 ms: 1.03x faster                                  |
| regex_effbot             | 3.55 ms                                                | 3.47 ms: 1.02x faster                                  |
| regex_v8                 | 22.3 ms                                                | 21.9 ms: 1.02x faster                                  |
| pathlib                  | 18.5 ms                                                | 18.2 ms: 1.02x faster                                  |
| dask                     | 365 ms                                                 | 358 ms: 1.02x faster                                   |
| pickle_pure_python       | 309 us                                                 | 306 us: 1.01x faster                                   |
| bench_thread_pool        | 827 us                                                 | 821 us: 1.01x faster                                   |
| sqlglot_optimize         | 53.3 ms                                                | 53.0 ms: 1.01x faster                                  |
| sqlglot_normalize        | 107 ms                                                 | 108 ms: 1.01x slower                                   |
| tomli_loads              | 2.22 sec                                               | 2.25 sec: 1.02x slower                                 |
| logging_silent           | 99.1 ns                                                | 101 ns: 1.02x slower                                   |
| sqlglot_transpile        | 1.64 ms                                                | 1.68 ms: 1.03x slower                                  |
| unpickle_list            | 4.95 us                                                | 5.08 us: 1.03x slower                                  |
| xml_etree_parse          | 154 ms                                                 | 158 ms: 1.03x slower                                   |
| go                       | 136 ms                                                 | 140 ms: 1.03x slower                                   |
| nqueens                  | 81.1 ms                                                | 83.7 ms: 1.03x slower                                  |
| sqlglot_parse            | 1.32 ms                                                | 1.37 ms: 1.04x slower                                  |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 742 ms: 1.04x slower                                   |
| nbody                    | 88.8 ms                                                | 92.6 ms: 1.04x slower                                  |
| unpickle_pure_python     | 218 us                                                 | 230 us: 1.05x slower                                   |
| hexiom                   | 6.12 ms                                                | 6.49 ms: 1.06x slower                                  |
| pidigits                 | 187 ms                                                 | 199 ms: 1.07x slower                                   |
| chaos                    | 63.5 ms                                                | 68.8 ms: 1.08x slower                                  |
| comprehensions           | 20.4 us                                                | 22.2 us: 1.08x slower                                  |
| mdp                      | 2.57 sec                                               | 2.81 sec: 1.10x slower                                 |
| async_tree_memoization   | 573 ms                                                 | 632 ms: 1.10x slower                                   |
| gc_traversal             | 3.84 ms                                                | 4.25 ms: 1.11x slower                                  |
| richards                 | 43.2 ms                                                | 47.9 ms: 1.11x slower                                  |
| async_tree_none          | 469 ms                                                 | 522 ms: 1.11x slower                                   |
| deltablue                | 3.52 ms                                                | 3.94 ms: 1.12x slower                                  |
| async_tree_io            | 1.16 sec                                               | 1.30 sec: 1.13x slower                                 |
| coroutines               | 22.4 ms                                                | 25.9 ms: 1.15x slower                                  |
| richards_super           | 49.0 ms                                                | 59.0 ms: 1.21x slower                                  |
| json_dumps               | 9.85 ms                                                | 12.7 ms: 1.29x slower                                  |
| mypy2                    | 344 ms                                                 | 529 ms: 1.54x slower                                   |
| asyncio_tcp_ssl          | 1.79 sec                                               | 3.14 sec: 1.75x slower                                 |
| asyncio_tcp              | 526 ms                                                 | 934 ms: 1.78x slower                                   |
| generators               | 31.1 ms                                                | 72.2 ms: 2.32x slower                                  |
| typing_runtime_protocols | 146 us                                                 | 493 us: 3.38x slower                                   |
| Geometric mean           | (ref)                                                  | 1.04x slower                                           |

Benchmark hidden because not significant (6): xml_etree_iterparse, raytrace, fannkuch, bench_mp_pool, meteor_contest, scimark_sparse_mat_mult
Ignored benchmarks (1) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: coverage
Ignored benchmarks (15) of results/bm-20231002-3.11.6-8b6ee5b/bm-20231002-linux-x86_64-python-v3.11.6-3.11.6-8b6ee5b.json: aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 78.64% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
