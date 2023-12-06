
# Results vs. 3.12.0

- fork: python
- ref: v3.11.5
- machine: linux-x86_64
- commit hash: cce6ba9
- commit date: 2023-08-24
- overall geometric mean: 1.03x slower
- HPT reliability: 77.58%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230824-linux-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 268 ms                                                 | 259 ms: 1.03x faster                                   |
| docutils       | 2.70 sec                                               | 2.59 sec: 1.04x faster                                 |
| tornado_http   | 99.6 ms                                                | 96.7 ms: 1.03x faster                                  |
| Geometric mean | (ref)                                                  | 1.04x faster                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230824-linux-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| float          | 80.7 ms                                                | 77.0 ms: 1.05x faster                                  |
| pidigits       | 187 ms                                                 | 190 ms: 1.02x slower                                   |
| nbody          | 88.8 ms                                                | 95.6 ms: 1.08x slower                                  |
| Geometric mean | (ref)                                                  | 1.01x slower                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230824-linux-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_effbot   | 3.55 ms                                                | 3.25 ms: 1.09x faster                                  |
| regex_compile  | 144 ms                                                 | 136 ms: 1.05x faster                                   |
| regex_dna      | 209 ms                                                 | 201 ms: 1.04x faster                                   |
| regex_v8       | 22.3 ms                                                | 21.8 ms: 1.03x faster                                  |
| Geometric mean | (ref)                                                  | 1.05x faster                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230824-linux-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| unpickle             | 15.0 us                                                | 13.3 us: 1.12x faster                                  |
| pickle_list          | 4.62 us                                                | 4.12 us: 1.12x faster                                  |
| xml_etree_generate   | 84.8 ms                                                | 76.2 ms: 1.11x faster                                  |
| xml_etree_process    | 58.6 ms                                                | 53.8 ms: 1.09x faster                                  |
| pickle               | 10.6 us                                                | 10.0 us: 1.06x faster                                  |
| pickle_dict          | 31.6 us                                                | 31.0 us: 1.02x faster                                  |
| pickle_pure_python   | 309 us                                                 | 306 us: 1.01x faster                                   |
| tomli_loads          | 2.22 sec                                               | 2.22 sec: 1.00x slower                                 |
| unpickle_list        | 4.95 us                                                | 5.00 us: 1.01x slower                                  |
| xml_etree_iterparse  | 104 ms                                                 | 105 ms: 1.01x slower                                   |
| json_loads           | 25.2 us                                                | 25.9 us: 1.03x slower                                  |
| xml_etree_parse      | 154 ms                                                 | 159 ms: 1.03x slower                                   |
| unpickle_pure_python | 218 us                                                 | 229 us: 1.05x slower                                   |
| json_dumps           | 9.85 ms                                                | 12.6 ms: 1.28x slower                                  |
| Geometric mean       | (ref)                                                  | 1.01x faster                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230824-linux-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.04 ms: 1.14x faster                                  |
| python_startup         | 9.47 ms                                                | 8.56 ms: 1.11x faster                                  |
| Geometric mean         | (ref)                                                  | 1.12x faster                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230824-linux-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|-----------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako      | 10.7 ms                                                | 9.99 ms: 1.07x faster                                  |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230824-linux-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_generators         | 440 ms                                                 | 361 ms: 1.22x faster                                   |
| python_startup_no_site   | 6.90 ms                                                | 6.04 ms: 1.14x faster                                  |
| unpickle                 | 15.0 us                                                | 13.3 us: 1.12x faster                                  |
| pickle_list              | 4.62 us                                                | 4.12 us: 1.12x faster                                  |
| xml_etree_generate       | 84.8 ms                                                | 76.2 ms: 1.11x faster                                  |
| python_startup           | 9.47 ms                                                | 8.56 ms: 1.11x faster                                  |
| sqlite_synth             | 2.76 us                                                | 2.52 us: 1.09x faster                                  |
| regex_effbot             | 3.55 ms                                                | 3.25 ms: 1.09x faster                                  |
| scimark_fft              | 358 ms                                                 | 329 ms: 1.09x faster                                   |
| xml_etree_process        | 58.6 ms                                                | 53.8 ms: 1.09x faster                                  |
| pyflate                  | 450 ms                                                 | 419 ms: 1.08x faster                                   |
| mako                     | 10.7 ms                                                | 9.99 ms: 1.07x faster                                  |
| dulwich_log              | 67.9 ms                                                | 63.8 ms: 1.06x faster                                  |
| scimark_lu               | 114 ms                                                 | 107 ms: 1.06x faster                                   |
| scimark_sor              | 125 ms                                                 | 117 ms: 1.06x faster                                   |
| gc_traversal             | 3.84 ms                                                | 3.64 ms: 1.06x faster                                  |
| pickle                   | 10.6 us                                                | 10.0 us: 1.06x faster                                  |
| regex_compile            | 144 ms                                                 | 136 ms: 1.05x faster                                   |
| logging_format           | 6.90 us                                                | 6.55 us: 1.05x faster                                  |
| deepcopy_reduce          | 3.14 us                                                | 2.99 us: 1.05x faster                                  |
| pprint_safe_repr         | 735 ms                                                 | 700 ms: 1.05x faster                                   |
| float                    | 80.7 ms                                                | 77.0 ms: 1.05x faster                                  |
| crypto_pyaes             | 77.2 ms                                                | 73.9 ms: 1.05x faster                                  |
| docutils                 | 2.70 sec                                               | 2.59 sec: 1.04x faster                                 |
| logging_simple           | 6.18 us                                                | 5.93 us: 1.04x faster                                  |
| telco                    | 6.87 ms                                                | 6.60 ms: 1.04x faster                                  |
| regex_dna                | 209 ms                                                 | 201 ms: 1.04x faster                                   |
| pprint_pformat           | 1.50 sec                                               | 1.45 sec: 1.03x faster                                 |
| 2to3                     | 268 ms                                                 | 259 ms: 1.03x faster                                   |
| scimark_monte_carlo      | 71.0 ms                                                | 68.8 ms: 1.03x faster                                  |
| sqlalchemy_imperative    | 18.4 ms                                                | 17.9 ms: 1.03x faster                                  |
| sqlalchemy_declarative   | 144 ms                                                 | 140 ms: 1.03x faster                                   |
| tornado_http             | 99.6 ms                                                | 96.7 ms: 1.03x faster                                  |
| regex_v8                 | 22.3 ms                                                | 21.8 ms: 1.03x faster                                  |
| create_gc_cycles         | 1.52 ms                                                | 1.48 ms: 1.03x faster                                  |
| pathlib                  | 18.5 ms                                                | 18.1 ms: 1.02x faster                                  |
| unpack_sequence          | 44.8 ns                                                | 43.9 ns: 1.02x faster                                  |
| spectral_norm            | 106 ms                                                 | 104 ms: 1.02x faster                                   |
| pickle_dict              | 31.6 us                                                | 31.0 us: 1.02x faster                                  |
| pycparser                | 1.15 sec                                               | 1.13 sec: 1.01x faster                                 |
| deepcopy                 | 355 us                                                 | 351 us: 1.01x faster                                   |
| fannkuch                 | 387 ms                                                 | 383 ms: 1.01x faster                                   |
| dask                     | 365 ms                                                 | 360 ms: 1.01x faster                                   |
| bench_thread_pool        | 827 us                                                 | 818 us: 1.01x faster                                   |
| pickle_pure_python       | 309 us                                                 | 306 us: 1.01x faster                                   |
| logging_silent           | 99.1 ns                                                | 98.6 ns: 1.01x faster                                  |
| sqlglot_optimize         | 53.3 ms                                                | 53.0 ms: 1.01x faster                                  |
| deepcopy_memo            | 37.4 us                                                | 37.2 us: 1.00x faster                                  |
| bench_mp_pool            | 24.0 ms                                                | 24.0 ms: 1.00x faster                                  |
| tomli_loads              | 2.22 sec                                               | 2.22 sec: 1.00x slower                                 |
| mdp                      | 2.57 sec                                               | 2.59 sec: 1.01x slower                                 |
| json                     | 4.77 ms                                                | 4.83 ms: 1.01x slower                                  |
| unpickle_list            | 4.95 us                                                | 5.00 us: 1.01x slower                                  |
| sqlglot_normalize        | 107 ms                                                 | 108 ms: 1.01x slower                                   |
| xml_etree_iterparse      | 104 ms                                                 | 105 ms: 1.01x slower                                   |
| pidigits                 | 187 ms                                                 | 190 ms: 1.02x slower                                   |
| sqlglot_transpile        | 1.64 ms                                                | 1.67 ms: 1.02x slower                                  |
| json_loads               | 25.2 us                                                | 25.9 us: 1.03x slower                                  |
| xml_etree_parse          | 154 ms                                                 | 159 ms: 1.03x slower                                   |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 740 ms: 1.04x slower                                   |
| nqueens                  | 81.1 ms                                                | 84.2 ms: 1.04x slower                                  |
| go                       | 136 ms                                                 | 141 ms: 1.04x slower                                   |
| sqlglot_parse            | 1.32 ms                                                | 1.37 ms: 1.04x slower                                  |
| hexiom                   | 6.12 ms                                                | 6.39 ms: 1.04x slower                                  |
| unpickle_pure_python     | 218 us                                                 | 229 us: 1.05x slower                                   |
| deltablue                | 3.52 ms                                                | 3.69 ms: 1.05x slower                                  |
| nbody                    | 88.8 ms                                                | 95.6 ms: 1.08x slower                                  |
| chaos                    | 63.5 ms                                                | 68.5 ms: 1.08x slower                                  |
| richards                 | 43.2 ms                                                | 47.1 ms: 1.09x slower                                  |
| comprehensions           | 20.4 us                                                | 22.7 us: 1.11x slower                                  |
| async_tree_memoization   | 573 ms                                                 | 641 ms: 1.12x slower                                   |
| async_tree_none          | 469 ms                                                 | 526 ms: 1.12x slower                                   |
| async_tree_io            | 1.16 sec                                               | 1.30 sec: 1.13x slower                                 |
| coroutines               | 22.4 ms                                                | 25.4 ms: 1.13x slower                                  |
| richards_super           | 49.0 ms                                                | 58.3 ms: 1.19x slower                                  |
| json_dumps               | 9.85 ms                                                | 12.6 ms: 1.28x slower                                  |
| mypy2                    | 344 ms                                                 | 532 ms: 1.55x slower                                   |
| asyncio_tcp              | 526 ms                                                 | 864 ms: 1.64x slower                                   |
| asyncio_tcp_ssl          | 1.79 sec                                               | 3.18 sec: 1.77x slower                                 |
| generators               | 31.1 ms                                                | 73.8 ms: 2.37x slower                                  |
| typing_runtime_protocols | 146 us                                                 | 493 us: 3.38x slower                                   |
| Geometric mean           | (ref)                                                  | 1.03x slower                                           |

Benchmark hidden because not significant (3): scimark_sparse_mat_mult, meteor_contest, raytrace
Ignored benchmarks (1) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: coverage
Ignored benchmarks (15) of results/bm-20230824-3.11.5-cce6ba9/bm-20230824-linux-x86_64-python-v3.11.5-3.11.5-cce6ba9.json: aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 77.58% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
