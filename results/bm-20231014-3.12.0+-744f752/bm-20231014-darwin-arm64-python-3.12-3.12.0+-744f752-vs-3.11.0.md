
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: darwin-arm64
- commit hash: 744f752
- commit date: 2023-10-14
- overall geometric mean: 1.02x faster
- HPT reliability: 62.76%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-darwin-arm64-python-3.12-3.12.0+-744f752 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| 2to3           | 161 ms                                                 | 169 ms: 1.05x slower                                 |
| docutils       | 1.47 sec                                               | 1.51 sec: 1.03x slower                               |
| Geometric mean | (ref)                                                  | 1.02x slower                                         |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-darwin-arm64-python-3.12-3.12.0+-744f752 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| pidigits       | 281 ms                                                 | 283 ms: 1.01x slower                                 |
| nbody          | 65.6 ms                                                | 68.7 ms: 1.05x slower                                |
| float          | 53.0 ms                                                | 56.6 ms: 1.07x slower                                |
| Geometric mean | (ref)                                                  | 1.04x slower                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-darwin-arm64-python-3.12-3.12.0+-744f752 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| regex_v8       | 16.1 ms                                                | 15.6 ms: 1.03x faster                                |
| regex_effbot   | 2.63 ms                                                | 2.57 ms: 1.03x faster                                |
| regex_dna      | 152 ms                                                 | 149 ms: 1.02x faster                                 |
| regex_compile  | 76.7 ms                                                | 75.4 ms: 1.02x faster                                |
| Geometric mean | (ref)                                                  | 1.02x faster                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-darwin-arm64-python-3.12-3.12.0+-744f752 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| json_dumps           | 7.63 ms                                                | 6.36 ms: 1.20x faster                                |
| unpickle_pure_python | 159 us                                                 | 144 us: 1.11x faster                                 |
| tomli_loads          | 1.47 sec                                               | 1.39 sec: 1.05x faster                               |
| pickle_pure_python   | 201 us                                                 | 190 us: 1.05x faster                                 |
| unpickle             | 9.67 us                                                | 9.29 us: 1.04x faster                                |
| pickle_dict          | 18.0 us                                                | 18.0 us: 1.00x slower                                |
| xml_etree_parse      | 108 ms                                                 | 109 ms: 1.01x slower                                 |
| pickle_list          | 2.81 us                                                | 2.87 us: 1.02x slower                                |
| pickle               | 7.15 us                                                | 7.38 us: 1.03x slower                                |
| xml_etree_iterparse  | 70.1 ms                                                | 74.4 ms: 1.06x slower                                |
| json_loads           | 16.1 us                                                | 17.7 us: 1.10x slower                                |
| xml_etree_process    | 35.1 ms                                                | 38.9 ms: 1.11x slower                                |
| xml_etree_generate   | 48.3 ms                                                | 56.0 ms: 1.16x slower                                |
| unpickle_list        | 2.65 us                                                | 3.21 us: 1.21x slower                                |
| Geometric mean       | (ref)                                                  | 1.02x slower                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-darwin-arm64-python-3.12-3.12.0+-744f752 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| python_startup         | 12.4 ms                                                | 12.6 ms: 1.02x slower                                |
| python_startup_no_site | 10.2 ms                                                | 10.3 ms: 1.02x slower                                |
| Geometric mean         | (ref)                                                  | 1.02x slower                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-darwin-arm64-python-3.12-3.12.0+-744f752 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------:|
| mako      | 8.53 ms                                                | 7.52 ms: 1.13x faster                                |

All benchmarks:
===============

| Benchmark                | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-darwin-arm64-python-3.12-3.12.0+-744f752 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 91.5 us: 3.67x faster                                |
| asyncio_tcp              | 651 ms                                                 | 463 ms: 1.41x faster                                 |
| json_dumps               | 7.63 ms                                                | 6.36 ms: 1.20x faster                                |
| unpack_sequence          | 34.1 ns                                                | 28.8 ns: 1.19x faster                                |
| chaos                    | 49.4 ms                                                | 42.2 ms: 1.17x faster                                |
| deltablue                | 2.81 ms                                                | 2.41 ms: 1.17x faster                                |
| richards_super           | 39.2 ms                                                | 33.9 ms: 1.16x faster                                |
| sqlglot_parse            | 959 us                                                 | 830 us: 1.16x faster                                 |
| coverage                 | 58.4 ms                                                | 50.8 ms: 1.15x faster                                |
| go                       | 109 ms                                                 | 94.5 ms: 1.15x faster                                |
| asyncio_tcp_ssl          | 1.44 sec                                               | 1.26 sec: 1.14x faster                               |
| mako                     | 8.53 ms                                                | 7.52 ms: 1.13x faster                                |
| sqlglot_transpile        | 1.12 ms                                                | 1.01 ms: 1.12x faster                                |
| unpickle_pure_python     | 159 us                                                 | 144 us: 1.11x faster                                 |
| hexiom                   | 4.72 ms                                                | 4.26 ms: 1.11x faster                                |
| generators               | 28.8 ms                                                | 26.1 ms: 1.10x faster                                |
| async_tree_memoization   | 336 ms                                                 | 311 ms: 1.08x faster                                 |
| async_tree_none          | 286 ms                                                 | 265 ms: 1.08x faster                                 |
| scimark_monte_carlo      | 46.5 ms                                                | 43.1 ms: 1.08x faster                                |
| comprehensions           | 16.1 us                                                | 15.1 us: 1.07x faster                                |
| async_tree_io            | 704 ms                                                 | 661 ms: 1.06x faster                                 |
| richards                 | 32.2 ms                                                | 30.3 ms: 1.06x faster                                |
| deepcopy_memo            | 26.3 us                                                | 24.9 us: 1.06x faster                                |
| tomli_loads              | 1.47 sec                                               | 1.39 sec: 1.05x faster                               |
| pickle_pure_python       | 201 us                                                 | 190 us: 1.05x faster                                 |
| sqlalchemy_imperative    | 7.20 ms                                                | 6.91 ms: 1.04x faster                                |
| unpickle                 | 9.67 us                                                | 9.29 us: 1.04x faster                                |
| pycparser                | 698 ms                                                 | 675 ms: 1.03x faster                                 |
| regex_v8                 | 16.1 ms                                                | 15.6 ms: 1.03x faster                                |
| coroutines               | 17.8 ms                                                | 17.3 ms: 1.03x faster                                |
| regex_effbot             | 2.63 ms                                                | 2.57 ms: 1.03x faster                                |
| mypy2                    | 195 ms                                                 | 190 ms: 1.02x faster                                 |
| create_gc_cycles         | 716 us                                                 | 699 us: 1.02x faster                                 |
| regex_dna                | 152 ms                                                 | 149 ms: 1.02x faster                                 |
| regex_compile            | 76.7 ms                                                | 75.4 ms: 1.02x faster                                |
| scimark_lu               | 73.3 ms                                                | 72.3 ms: 1.01x faster                                |
| async_tree_cpu_io_mixed  | 533 ms                                                 | 527 ms: 1.01x faster                                 |
| gc_traversal             | 2.42 ms                                                | 2.40 ms: 1.01x faster                                |
| nqueens                  | 59.8 ms                                                | 59.5 ms: 1.00x faster                                |
| meteor_contest           | 73.5 ms                                                | 73.3 ms: 1.00x faster                                |
| raytrace                 | 207 ms                                                 | 207 ms: 1.00x slower                                 |
| scimark_sparse_mat_mult  | 3.19 ms                                                | 3.20 ms: 1.00x slower                                |
| pickle_dict              | 18.0 us                                                | 18.0 us: 1.00x slower                                |
| fannkuch                 | 261 ms                                                 | 263 ms: 1.00x slower                                 |
| crypto_pyaes             | 51.7 ms                                                | 52.0 ms: 1.01x slower                                |
| pidigits                 | 281 ms                                                 | 283 ms: 1.01x slower                                 |
| xml_etree_parse          | 108 ms                                                 | 109 ms: 1.01x slower                                 |
| scimark_fft              | 200 ms                                                 | 201 ms: 1.01x slower                                 |
| python_startup           | 12.4 ms                                                | 12.6 ms: 1.02x slower                                |
| logging_format           | 3.78 us                                                | 3.84 us: 1.02x slower                                |
| deepcopy                 | 223 us                                                 | 226 us: 1.02x slower                                 |
| python_startup_no_site   | 10.2 ms                                                | 10.3 ms: 1.02x slower                                |
| pyflate                  | 310 ms                                                 | 316 ms: 1.02x slower                                 |
| pickle_list              | 2.81 us                                                | 2.87 us: 1.02x slower                                |
| bench_thread_pool        | 474 us                                                 | 485 us: 1.02x slower                                 |
| docutils                 | 1.47 sec                                               | 1.51 sec: 1.03x slower                               |
| spectral_norm            | 72.6 ms                                                | 74.9 ms: 1.03x slower                                |
| pickle                   | 7.15 us                                                | 7.38 us: 1.03x slower                                |
| sqlalchemy_declarative   | 62.6 ms                                                | 65.0 ms: 1.04x slower                                |
| bench_mp_pool            | 43.9 ms                                                | 45.7 ms: 1.04x slower                                |
| scimark_sor              | 82.6 ms                                                | 86.3 ms: 1.04x slower                                |
| 2to3                     | 161 ms                                                 | 169 ms: 1.05x slower                                 |
| nbody                    | 65.6 ms                                                | 68.7 ms: 1.05x slower                                |
| pprint_pformat           | 954 ms                                                 | 1.00 sec: 1.05x slower                               |
| pprint_safe_repr         | 466 ms                                                 | 493 ms: 1.06x slower                                 |
| xml_etree_iterparse      | 70.1 ms                                                | 74.4 ms: 1.06x slower                                |
| float                    | 53.0 ms                                                | 56.6 ms: 1.07x slower                                |
| deepcopy_reduce          | 1.91 us                                                | 2.05 us: 1.07x slower                                |
| json                     | 2.78 ms                                                | 2.98 ms: 1.07x slower                                |
| mdp                      | 1.55 sec                                               | 1.66 sec: 1.07x slower                               |
| pathlib                  | 27.2 ms                                                | 29.3 ms: 1.08x slower                                |
| sqlglot_normalize        | 171 ms                                                 | 185 ms: 1.08x slower                                 |
| telco                    | 3.41 ms                                                | 3.73 ms: 1.10x slower                                |
| json_loads               | 16.1 us                                                | 17.7 us: 1.10x slower                                |
| sqlglot_optimize         | 31.1 ms                                                | 34.2 ms: 1.10x slower                                |
| xml_etree_process        | 35.1 ms                                                | 38.9 ms: 1.11x slower                                |
| xml_etree_generate       | 48.3 ms                                                | 56.0 ms: 1.16x slower                                |
| unpickle_list            | 2.65 us                                                | 3.21 us: 1.21x slower                                |
| sqlite_synth             | 1.27 us                                                | 1.59 us: 1.25x slower                                |
| async_generators         | 196 ms                                                 | 306 ms: 1.56x slower                                 |
| Geometric mean           | (ref)                                                  | 1.02x faster                                         |

Benchmark hidden because not significant (4): tornado_http, dulwich_log, logging_silent, logging_simple
Ignored benchmarks (14) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
Ignored benchmarks (1) of results/bm-20231014-3.12.0+-744f752/bm-20231014-darwin-arm64-python-3.12-3.12.0+-744f752.json: dask


# HPT report

- Reliability score: 62.76% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
