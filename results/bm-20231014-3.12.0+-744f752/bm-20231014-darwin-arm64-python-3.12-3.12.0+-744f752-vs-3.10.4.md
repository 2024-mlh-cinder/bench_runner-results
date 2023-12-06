
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: darwin-arm64
- commit hash: 744f752
- commit date: 2023-10-14
- overall geometric mean: 1.24x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.16x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-darwin-arm64-python-3.12-3.12.0+-744f752 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| 2to3           | 202 ms                                                 | 169 ms: 1.20x faster                                 |
| docutils       | 1.78 sec                                               | 1.51 sec: 1.18x faster                               |
| tornado_http   | 91.9 ms                                                | 70.3 ms: 1.31x faster                                |
| Geometric mean | (ref)                                                  | 1.23x faster                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-darwin-arm64-python-3.12-3.12.0+-744f752 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| nbody          | 94.1 ms                                                | 68.7 ms: 1.37x faster                                |
| float          | 72.3 ms                                                | 56.6 ms: 1.28x faster                                |
| pidigits       | 282 ms                                                 | 283 ms: 1.00x slower                                 |
| Geometric mean | (ref)                                                  | 1.20x faster                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-darwin-arm64-python-3.12-3.12.0+-744f752 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| regex_compile  | 96.6 ms                                                | 75.4 ms: 1.28x faster                                |
| regex_v8       | 17.5 ms                                                | 15.6 ms: 1.12x faster                                |
| regex_dna      | 160 ms                                                 | 149 ms: 1.07x faster                                 |
| regex_effbot   | 2.45 ms                                                | 2.57 ms: 1.05x slower                                |
| Geometric mean | (ref)                                                  | 1.10x faster                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-darwin-arm64-python-3.12-3.12.0+-744f752 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| pickle_pure_python   | 284 us                                                 | 190 us: 1.49x faster                                 |
| unpickle_pure_python | 203 us                                                 | 144 us: 1.41x faster                                 |
| json_dumps           | 8.38 ms                                                | 6.36 ms: 1.32x faster                                |
| tomli_loads          | 1.76 sec                                               | 1.39 sec: 1.27x faster                               |
| xml_etree_process    | 45.1 ms                                                | 38.9 ms: 1.16x faster                                |
| unpickle             | 9.77 us                                                | 9.29 us: 1.05x faster                                |
| pickle               | 7.36 us                                                | 7.38 us: 1.00x slower                                |
| xml_etree_parse      | 107 ms                                                 | 109 ms: 1.01x slower                                 |
| pickle_list          | 2.83 us                                                | 2.87 us: 1.01x slower                                |
| pickle_dict          | 17.8 us                                                | 18.0 us: 1.01x slower                                |
| xml_etree_iterparse  | 72.6 ms                                                | 74.4 ms: 1.02x slower                                |
| xml_etree_generate   | 54.3 ms                                                | 56.0 ms: 1.03x slower                                |
| json_loads           | 16.9 us                                                | 17.7 us: 1.05x slower                                |
| unpickle_list        | 2.66 us                                                | 3.21 us: 1.21x slower                                |
| Geometric mean       | (ref)                                                  | 1.08x faster                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-darwin-arm64-python-3.12-3.12.0+-744f752 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| python_startup_no_site | 9.73 ms                                                | 10.3 ms: 1.06x slower                                |
| Geometric mean         | (ref)                                                  | 1.03x slower                                         |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-darwin-arm64-python-3.12-3.12.0+-744f752 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------:|
| mako      | 10.5 ms                                                | 7.52 ms: 1.39x faster                                |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-darwin-arm64-python-3.12-3.12.0+-744f752 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| typing_runtime_protocols | 344 us                                                 | 91.5 us: 3.76x faster                                |
| deltablue                | 5.15 ms                                                | 2.41 ms: 2.14x faster                                |
| richards_super           | 60.7 ms                                                | 33.9 ms: 1.79x faster                                |
| logging_silent           | 119 ns                                                 | 68.0 ns: 1.75x faster                                |
| go                       | 165 ms                                                 | 94.5 ms: 1.74x faster                                |
| richards                 | 51.4 ms                                                | 30.3 ms: 1.70x faster                                |
| scimark_monte_carlo      | 72.2 ms                                                | 43.1 ms: 1.67x faster                                |
| mypy2                    | 308 ms                                                 | 190 ms: 1.62x faster                                 |
| sqlglot_parse            | 1.33 ms                                                | 830 us: 1.60x faster                                 |
| chaos                    | 66.8 ms                                                | 42.2 ms: 1.58x faster                                |
| async_tree_memoization   | 493 ms                                                 | 311 ms: 1.58x faster                                 |
| raytrace                 | 328 ms                                                 | 207 ms: 1.58x faster                                 |
| async_tree_io            | 1.02 sec                                               | 661 ms: 1.54x faster                                 |
| sqlglot_transpile        | 1.54 ms                                                | 1.01 ms: 1.53x faster                                |
| scimark_lu               | 110 ms                                                 | 72.3 ms: 1.52x faster                                |
| async_tree_none          | 402 ms                                                 | 265 ms: 1.52x faster                                 |
| crypto_pyaes             | 78.0 ms                                                | 52.0 ms: 1.50x faster                                |
| pickle_pure_python       | 284 us                                                 | 190 us: 1.49x faster                                 |
| hexiom                   | 6.32 ms                                                | 4.26 ms: 1.48x faster                                |
| scimark_sor              | 127 ms                                                 | 86.3 ms: 1.47x faster                                |
| asyncio_tcp              | 673 ms                                                 | 463 ms: 1.45x faster                                 |
| pyflate                  | 453 ms                                                 | 316 ms: 1.44x faster                                 |
| unpickle_pure_python     | 203 us                                                 | 144 us: 1.41x faster                                 |
| mako                     | 10.5 ms                                                | 7.52 ms: 1.39x faster                                |
| deepcopy_memo            | 34.5 us                                                | 24.9 us: 1.38x faster                                |
| nbody                    | 94.1 ms                                                | 68.7 ms: 1.37x faster                                |
| pycparser                | 915 ms                                                 | 675 ms: 1.36x faster                                 |
| unpack_sequence          | 38.7 ns                                                | 28.8 ns: 1.34x faster                                |
| json_dumps               | 8.38 ms                                                | 6.36 ms: 1.32x faster                                |
| tornado_http             | 91.9 ms                                                | 70.3 ms: 1.31x faster                                |
| sqlalchemy_imperative    | 9.03 ms                                                | 6.91 ms: 1.31x faster                                |
| logging_format           | 5.01 us                                                | 3.84 us: 1.31x faster                                |
| asyncio_tcp_ssl          | 1.64 sec                                               | 1.26 sec: 1.31x faster                               |
| logging_simple           | 4.63 us                                                | 3.56 us: 1.30x faster                                |
| spectral_norm            | 96.4 ms                                                | 74.9 ms: 1.29x faster                                |
| regex_compile            | 96.6 ms                                                | 75.4 ms: 1.28x faster                                |
| float                    | 72.3 ms                                                | 56.6 ms: 1.28x faster                                |
| async_tree_cpu_io_mixed  | 670 ms                                                 | 527 ms: 1.27x faster                                 |
| tomli_loads              | 1.76 sec                                               | 1.39 sec: 1.27x faster                               |
| generators               | 32.9 ms                                                | 26.1 ms: 1.26x faster                                |
| create_gc_cycles         | 876 us                                                 | 699 us: 1.25x faster                                 |
| pprint_pformat           | 1.24 sec                                               | 1.00 sec: 1.24x faster                               |
| pprint_safe_repr         | 609 ms                                                 | 493 ms: 1.23x faster                                 |
| dulwich_log              | 37.1 ms                                                | 30.2 ms: 1.23x faster                                |
| deepcopy                 | 278 us                                                 | 226 us: 1.23x faster                                 |
| fannkuch                 | 317 ms                                                 | 263 ms: 1.21x faster                                 |
| 2to3                     | 202 ms                                                 | 169 ms: 1.20x faster                                 |
| docutils                 | 1.78 sec                                               | 1.51 sec: 1.18x faster                               |
| comprehensions           | 17.7 us                                                | 15.1 us: 1.17x faster                                |
| deepcopy_reduce          | 2.38 us                                                | 2.05 us: 1.17x faster                                |
| coroutines               | 20.2 ms                                                | 17.3 ms: 1.16x faster                                |
| xml_etree_process        | 45.1 ms                                                | 38.9 ms: 1.16x faster                                |
| scimark_fft              | 232 ms                                                 | 201 ms: 1.15x faster                                 |
| sqlalchemy_declarative   | 74.8 ms                                                | 65.0 ms: 1.15x faster                                |
| nqueens                  | 68.1 ms                                                | 59.5 ms: 1.14x faster                                |
| dask                     | 258 ms                                                 | 228 ms: 1.13x faster                                 |
| bench_thread_pool        | 548 us                                                 | 485 us: 1.13x faster                                 |
| regex_v8                 | 17.5 ms                                                | 15.6 ms: 1.12x faster                                |
| sqlglot_optimize         | 38.0 ms                                                | 34.2 ms: 1.11x faster                                |
| scimark_sparse_mat_mult  | 3.47 ms                                                | 3.20 ms: 1.08x faster                                |
| regex_dna                | 160 ms                                                 | 149 ms: 1.07x faster                                 |
| meteor_contest           | 78.6 ms                                                | 73.3 ms: 1.07x faster                                |
| sqlglot_normalize        | 197 ms                                                 | 185 ms: 1.06x faster                                 |
| unpickle                 | 9.77 us                                                | 9.29 us: 1.05x faster                                |
| json                     | 3.10 ms                                                | 2.98 ms: 1.04x faster                                |
| pidigits                 | 282 ms                                                 | 283 ms: 1.00x slower                                 |
| pickle                   | 7.36 us                                                | 7.38 us: 1.00x slower                                |
| xml_etree_parse          | 107 ms                                                 | 109 ms: 1.01x slower                                 |
| pickle_list              | 2.83 us                                                | 2.87 us: 1.01x slower                                |
| telco                    | 3.68 ms                                                | 3.73 ms: 1.01x slower                                |
| pickle_dict              | 17.8 us                                                | 18.0 us: 1.01x slower                                |
| pathlib                  | 28.8 ms                                                | 29.3 ms: 1.02x slower                                |
| xml_etree_iterparse      | 72.6 ms                                                | 74.4 ms: 1.02x slower                                |
| xml_etree_generate       | 54.3 ms                                                | 56.0 ms: 1.03x slower                                |
| json_loads               | 16.9 us                                                | 17.7 us: 1.05x slower                                |
| regex_effbot             | 2.45 ms                                                | 2.57 ms: 1.05x slower                                |
| python_startup_no_site   | 9.73 ms                                                | 10.3 ms: 1.06x slower                                |
| sqlite_synth             | 1.47 us                                                | 1.59 us: 1.08x slower                                |
| bench_mp_pool            | 41.0 ms                                                | 45.7 ms: 1.12x slower                                |
| unpickle_list            | 2.66 us                                                | 3.21 us: 1.21x slower                                |
| coverage                 | 40.8 ms                                                | 50.8 ms: 1.24x slower                                |
| async_generators         | 233 ms                                                 | 306 ms: 1.31x slower                                 |
| Geometric mean           | (ref)                                                  | 1.24x faster                                         |

Benchmark hidden because not significant (3): mdp, python_startup, gc_traversal
Ignored benchmarks (14) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.20x
- 95% likely to have a speedup of 1.19x
- 99% likely to have a speedup of 1.16x
