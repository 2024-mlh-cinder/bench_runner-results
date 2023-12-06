
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: darwin-arm64
- commit hash: e9a9052
- commit date: 2023-09-15
- overall geometric mean: 1.22x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.15x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-darwin-arm64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| 2to3           | 202 ms                                                 | 170 ms: 1.19x faster                                    |
| docutils       | 1.78 sec                                               | 1.53 sec: 1.17x faster                                  |
| tornado_http   | 91.9 ms                                                | 71.1 ms: 1.29x faster                                   |
| Geometric mean | (ref)                                                  | 1.22x faster                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-darwin-arm64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| nbody          | 94.1 ms                                                | 68.4 ms: 1.38x faster                                   |
| float          | 72.3 ms                                                | 58.1 ms: 1.24x faster                                   |
| pidigits       | 282 ms                                                 | 282 ms: 1.00x faster                                    |
| Geometric mean | (ref)                                                  | 1.20x faster                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-darwin-arm64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_compile  | 96.6 ms                                                | 75.5 ms: 1.28x faster                                   |
| regex_v8       | 17.5 ms                                                | 15.8 ms: 1.11x faster                                   |
| regex_dna      | 160 ms                                                 | 151 ms: 1.06x faster                                    |
| regex_effbot   | 2.45 ms                                                | 2.58 ms: 1.06x slower                                   |
| Geometric mean | (ref)                                                  | 1.09x faster                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-darwin-arm64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| pickle_pure_python   | 284 us                                                 | 188 us: 1.51x faster                                    |
| unpickle_pure_python | 203 us                                                 | 144 us: 1.41x faster                                    |
| json_dumps           | 8.38 ms                                                | 6.45 ms: 1.30x faster                                   |
| tomli_loads          | 1.76 sec                                               | 1.38 sec: 1.28x faster                                  |
| xml_etree_process    | 45.1 ms                                                | 38.5 ms: 1.17x faster                                   |
| unpickle             | 9.77 us                                                | 9.22 us: 1.06x faster                                   |
| pickle               | 7.36 us                                                | 7.40 us: 1.01x slower                                   |
| xml_etree_parse      | 107 ms                                                 | 108 ms: 1.01x slower                                    |
| pickle_dict          | 17.8 us                                                | 18.0 us: 1.01x slower                                   |
| xml_etree_iterparse  | 72.6 ms                                                | 73.9 ms: 1.02x slower                                   |
| pickle_list          | 2.83 us                                                | 2.89 us: 1.02x slower                                   |
| xml_etree_generate   | 54.3 ms                                                | 55.9 ms: 1.03x slower                                   |
| json_loads           | 16.9 us                                                | 17.6 us: 1.04x slower                                   |
| unpickle_list        | 2.66 us                                                | 3.21 us: 1.21x slower                                   |
| Geometric mean       | (ref)                                                  | 1.09x faster                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-darwin-arm64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| python_startup | 12.6 ms                                                | 11.9 ms: 1.06x faster                                   |
| Geometric mean | (ref)                                                  | 1.03x faster                                            |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-darwin-arm64-python-3.12-3.12.0rc2+-e9a9052 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------:|
| mako      | 10.5 ms                                                | 7.53 ms: 1.39x faster                                   |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-darwin-arm64-python-3.12-3.12.0rc2+-e9a9052 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| typing_runtime_protocols | 344 us                                                 | 90.7 us: 3.80x faster                                   |
| deltablue                | 5.15 ms                                                | 2.58 ms: 2.00x faster                                   |
| logging_silent           | 119 ns                                                 | 67.7 ns: 1.76x faster                                   |
| richards_super           | 60.7 ms                                                | 34.8 ms: 1.74x faster                                   |
| richards                 | 51.4 ms                                                | 31.1 ms: 1.65x faster                                   |
| async_tree_memoization   | 493 ms                                                 | 306 ms: 1.61x faster                                    |
| asyncio_tcp              | 673 ms                                                 | 432 ms: 1.56x faster                                    |
| async_tree_none          | 402 ms                                                 | 259 ms: 1.55x faster                                    |
| async_tree_io            | 1.02 sec                                               | 661 ms: 1.54x faster                                    |
| go                       | 165 ms                                                 | 107 ms: 1.54x faster                                    |
| scimark_lu               | 110 ms                                                 | 71.7 ms: 1.53x faster                                   |
| pickle_pure_python       | 284 us                                                 | 188 us: 1.51x faster                                    |
| crypto_pyaes             | 78.0 ms                                                | 52.1 ms: 1.50x faster                                   |
| hexiom                   | 6.32 ms                                                | 4.23 ms: 1.49x faster                                   |
| sqlglot_parse            | 1.33 ms                                                | 894 us: 1.49x faster                                    |
| chaos                    | 66.8 ms                                                | 45.1 ms: 1.48x faster                                   |
| scimark_monte_carlo      | 72.2 ms                                                | 50.0 ms: 1.45x faster                                   |
| sqlglot_transpile        | 1.54 ms                                                | 1.07 ms: 1.43x faster                                   |
| unpickle_pure_python     | 203 us                                                 | 144 us: 1.41x faster                                    |
| deepcopy_memo            | 34.5 us                                                | 24.6 us: 1.40x faster                                   |
| mako                     | 10.5 ms                                                | 7.53 ms: 1.39x faster                                   |
| pyflate                  | 453 ms                                                 | 327 ms: 1.39x faster                                    |
| nbody                    | 94.1 ms                                                | 68.4 ms: 1.38x faster                                   |
| pycparser                | 915 ms                                                 | 666 ms: 1.37x faster                                    |
| unpack_sequence          | 38.7 ns                                                | 28.7 ns: 1.35x faster                                   |
| scimark_sor              | 127 ms                                                 | 94.4 ms: 1.34x faster                                   |
| raytrace                 | 328 ms                                                 | 246 ms: 1.34x faster                                    |
| asyncio_tcp_ssl          | 1.64 sec                                               | 1.24 sec: 1.33x faster                                  |
| json_dumps               | 8.38 ms                                                | 6.45 ms: 1.30x faster                                   |
| sqlalchemy_imperative    | 9.03 ms                                                | 6.97 ms: 1.30x faster                                   |
| tornado_http             | 91.9 ms                                                | 71.1 ms: 1.29x faster                                   |
| spectral_norm            | 96.4 ms                                                | 74.7 ms: 1.29x faster                                   |
| async_tree_cpu_io_mixed  | 670 ms                                                 | 521 ms: 1.29x faster                                    |
| regex_compile            | 96.6 ms                                                | 75.5 ms: 1.28x faster                                   |
| tomli_loads              | 1.76 sec                                               | 1.38 sec: 1.28x faster                                  |
| logging_format           | 5.01 us                                                | 3.96 us: 1.26x faster                                   |
| logging_simple           | 4.63 us                                                | 3.68 us: 1.26x faster                                   |
| create_gc_cycles         | 876 us                                                 | 704 us: 1.25x faster                                    |
| float                    | 72.3 ms                                                | 58.1 ms: 1.24x faster                                   |
| pprint_pformat           | 1.24 sec                                               | 1.00 sec: 1.24x faster                                  |
| pprint_safe_repr         | 609 ms                                                 | 492 ms: 1.24x faster                                    |
| deepcopy                 | 278 us                                                 | 225 us: 1.23x faster                                    |
| dulwich_log              | 37.1 ms                                                | 30.3 ms: 1.22x faster                                   |
| mypy2                    | 308 ms                                                 | 256 ms: 1.20x faster                                    |
| fannkuch                 | 317 ms                                                 | 266 ms: 1.19x faster                                    |
| 2to3                     | 202 ms                                                 | 170 ms: 1.19x faster                                    |
| deepcopy_reduce          | 2.38 us                                                | 2.03 us: 1.17x faster                                   |
| scimark_fft              | 232 ms                                                 | 198 ms: 1.17x faster                                    |
| xml_etree_process        | 45.1 ms                                                | 38.5 ms: 1.17x faster                                   |
| docutils                 | 1.78 sec                                               | 1.53 sec: 1.17x faster                                  |
| generators               | 32.9 ms                                                | 28.3 ms: 1.16x faster                                   |
| sqlalchemy_declarative   | 74.8 ms                                                | 65.0 ms: 1.15x faster                                   |
| bench_thread_pool        | 548 us                                                 | 487 us: 1.13x faster                                    |
| comprehensions           | 17.7 us                                                | 15.7 us: 1.13x faster                                   |
| nqueens                  | 68.1 ms                                                | 60.5 ms: 1.13x faster                                   |
| regex_v8                 | 17.5 ms                                                | 15.8 ms: 1.11x faster                                   |
| sqlglot_optimize         | 38.0 ms                                                | 34.2 ms: 1.11x faster                                   |
| scimark_sparse_mat_mult  | 3.47 ms                                                | 3.14 ms: 1.11x faster                                   |
| meteor_contest           | 78.6 ms                                                | 72.9 ms: 1.08x faster                                   |
| coroutines               | 20.2 ms                                                | 19.0 ms: 1.06x faster                                   |
| unpickle                 | 9.77 us                                                | 9.22 us: 1.06x faster                                   |
| sqlglot_normalize        | 197 ms                                                 | 186 ms: 1.06x faster                                    |
| regex_dna                | 160 ms                                                 | 151 ms: 1.06x faster                                    |
| python_startup           | 12.6 ms                                                | 11.9 ms: 1.06x faster                                   |
| json                     | 3.10 ms                                                | 3.04 ms: 1.02x faster                                   |
| mdp                      | 1.67 sec                                               | 1.65 sec: 1.01x faster                                  |
| pidigits                 | 282 ms                                                 | 282 ms: 1.00x faster                                    |
| pickle                   | 7.36 us                                                | 7.40 us: 1.01x slower                                   |
| xml_etree_parse          | 107 ms                                                 | 108 ms: 1.01x slower                                    |
| telco                    | 3.68 ms                                                | 3.72 ms: 1.01x slower                                   |
| pickle_dict              | 17.8 us                                                | 18.0 us: 1.01x slower                                   |
| xml_etree_iterparse      | 72.6 ms                                                | 73.9 ms: 1.02x slower                                   |
| pickle_list              | 2.83 us                                                | 2.89 us: 1.02x slower                                   |
| xml_etree_generate       | 54.3 ms                                                | 55.9 ms: 1.03x slower                                   |
| json_loads               | 16.9 us                                                | 17.6 us: 1.04x slower                                   |
| regex_effbot             | 2.45 ms                                                | 2.58 ms: 1.06x slower                                   |
| sqlite_synth             | 1.47 us                                                | 1.58 us: 1.07x slower                                   |
| pathlib                  | 28.8 ms                                                | 32.7 ms: 1.13x slower                                   |
| bench_mp_pool            | 41.0 ms                                                | 46.5 ms: 1.13x slower                                   |
| unpickle_list            | 2.66 us                                                | 3.21 us: 1.21x slower                                   |
| coverage                 | 40.8 ms                                                | 51.3 ms: 1.26x slower                                   |
| dask                     | 258 ms                                                 | 329 ms: 1.28x slower                                    |
| async_generators         | 233 ms                                                 | 304 ms: 1.30x slower                                    |
| Geometric mean           | (ref)                                                  | 1.22x faster                                            |

Benchmark hidden because not significant (2): gc_traversal, python_startup_no_site
Ignored benchmarks (14) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.19x
- 95% likely to have a speedup of 1.17x
- 99% likely to have a speedup of 1.15x
