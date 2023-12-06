
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: darwin-arm64
- commit hash: 0553fdf
- commit date: 2023-09-10
- overall geometric mean: 1.23x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.14x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230910-darwin-arm64-python-main-3.13.0a0-0553fdf |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| docutils       | 1.78 sec                                               | 1.50 sec: 1.19x faster                                |
| tornado_http   | 91.9 ms                                                | 71.1 ms: 1.29x faster                                 |
| Geometric mean | (ref)                                                  | 1.24x faster                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230910-darwin-arm64-python-main-3.13.0a0-0553fdf |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| nbody          | 94.1 ms                                                | 71.0 ms: 1.33x faster                                 |
| float          | 72.3 ms                                                | 55.2 ms: 1.31x faster                                 |
| pidigits       | 282 ms                                                 | 282 ms: 1.00x slower                                  |
| Geometric mean | (ref)                                                  | 1.20x faster                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230910-darwin-arm64-python-main-3.13.0a0-0553fdf |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_compile  | 96.6 ms                                                | 77.3 ms: 1.25x faster                                 |
| regex_dna      | 160 ms                                                 | 140 ms: 1.14x faster                                  |
| regex_v8       | 17.5 ms                                                | 16.3 ms: 1.07x faster                                 |
| regex_effbot   | 2.45 ms                                                | 2.51 ms: 1.03x slower                                 |
| Geometric mean | (ref)                                                  | 1.10x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230910-darwin-arm64-python-main-3.13.0a0-0553fdf |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_pure_python   | 284 us                                                 | 194 us: 1.46x faster                                  |
| json_dumps           | 8.38 ms                                                | 6.48 ms: 1.29x faster                                 |
| unpickle_pure_python | 203 us                                                 | 157 us: 1.29x faster                                  |
| xml_etree_process    | 45.1 ms                                                | 39.0 ms: 1.15x faster                                 |
| tomli_loads          | 1.76 sec                                               | 1.54 sec: 1.14x faster                                |
| unpickle             | 9.77 us                                                | 9.17 us: 1.07x faster                                 |
| pickle               | 7.36 us                                                | 7.44 us: 1.01x slower                                 |
| pickle_dict          | 17.8 us                                                | 18.1 us: 1.02x slower                                 |
| xml_etree_parse      | 107 ms                                                 | 110 ms: 1.02x slower                                  |
| json_loads           | 16.9 us                                                | 17.5 us: 1.04x slower                                 |
| xml_etree_iterparse  | 72.6 ms                                                | 75.4 ms: 1.04x slower                                 |
| xml_etree_generate   | 54.3 ms                                                | 57.2 ms: 1.05x slower                                 |
| unpickle_list        | 2.66 us                                                | 3.14 us: 1.18x slower                                 |
| Geometric mean       | (ref)                                                  | 1.07x faster                                          |

Benchmark hidden because not significant (1): pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230910-darwin-arm64-python-main-3.13.0a0-0553fdf |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup         | 12.6 ms                                                | 12.1 ms: 1.04x faster                                 |
| python_startup_no_site | 9.73 ms                                                | 9.49 ms: 1.02x faster                                 |
| Geometric mean         | (ref)                                                  | 1.03x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230910-darwin-arm64-python-main-3.13.0a0-0553fdf |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 10.5 ms                                                | 7.34 ms: 1.43x faster                                 |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230910-darwin-arm64-python-main-3.13.0a0-0553fdf |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| typing_runtime_protocols | 344 us                                                 | 92.4 us: 3.72x faster                                 |
| deltablue                | 5.15 ms                                                | 2.45 ms: 2.10x faster                                 |
| raytrace                 | 328 ms                                                 | 177 ms: 1.85x faster                                  |
| crypto_pyaes             | 78.0 ms                                                | 46.8 ms: 1.67x faster                                 |
| logging_silent           | 119 ns                                                 | 71.5 ns: 1.66x faster                                 |
| sqlglot_parse            | 1.33 ms                                                | 800 us: 1.66x faster                                  |
| chaos                    | 66.8 ms                                                | 40.6 ms: 1.65x faster                                 |
| richards_super           | 60.7 ms                                                | 37.2 ms: 1.63x faster                                 |
| mypy2                    | 308 ms                                                 | 190 ms: 1.62x faster                                  |
| asyncio_tcp              | 673 ms                                                 | 415 ms: 1.62x faster                                  |
| async_tree_none          | 402 ms                                                 | 251 ms: 1.60x faster                                  |
| scimark_monte_carlo      | 72.2 ms                                                | 45.2 ms: 1.60x faster                                 |
| sqlglot_transpile        | 1.54 ms                                                | 975 us: 1.58x faster                                  |
| go                       | 165 ms                                                 | 105 ms: 1.57x faster                                  |
| scimark_lu               | 110 ms                                                 | 70.6 ms: 1.56x faster                                 |
| richards                 | 51.4 ms                                                | 33.7 ms: 1.52x faster                                 |
| async_tree_memoization   | 493 ms                                                 | 328 ms: 1.50x faster                                  |
| unpack_sequence          | 38.7 ns                                                | 26.2 ns: 1.47x faster                                 |
| pickle_pure_python       | 284 us                                                 | 194 us: 1.46x faster                                  |
| async_tree_io            | 1.02 sec                                               | 698 ms: 1.46x faster                                  |
| deepcopy_memo            | 34.5 us                                                | 24.0 us: 1.44x faster                                 |
| mako                     | 10.5 ms                                                | 7.34 ms: 1.43x faster                                 |
| spectral_norm            | 96.4 ms                                                | 71.4 ms: 1.35x faster                                 |
| generators               | 32.9 ms                                                | 24.5 ms: 1.34x faster                                 |
| hexiom                   | 6.32 ms                                                | 4.72 ms: 1.34x faster                                 |
| pyflate                  | 453 ms                                                 | 341 ms: 1.33x faster                                  |
| pycparser                | 915 ms                                                 | 688 ms: 1.33x faster                                  |
| nbody                    | 94.1 ms                                                | 71.0 ms: 1.33x faster                                 |
| float                    | 72.3 ms                                                | 55.2 ms: 1.31x faster                                 |
| tornado_http             | 91.9 ms                                                | 71.1 ms: 1.29x faster                                 |
| json_dumps               | 8.38 ms                                                | 6.48 ms: 1.29x faster                                 |
| unpickle_pure_python     | 203 us                                                 | 157 us: 1.29x faster                                  |
| asyncio_tcp_ssl          | 1.64 sec                                               | 1.27 sec: 1.29x faster                                |
| logging_format           | 5.01 us                                                | 3.90 us: 1.29x faster                                 |
| logging_simple           | 4.63 us                                                | 3.61 us: 1.28x faster                                 |
| async_tree_cpu_io_mixed  | 670 ms                                                 | 523 ms: 1.28x faster                                  |
| regex_compile            | 96.6 ms                                                | 77.3 ms: 1.25x faster                                 |
| deepcopy                 | 278 us                                                 | 224 us: 1.24x faster                                  |
| create_gc_cycles         | 876 us                                                 | 710 us: 1.23x faster                                  |
| pprint_pformat           | 1.24 sec                                               | 1.01 sec: 1.23x faster                                |
| pprint_safe_repr         | 609 ms                                                 | 498 ms: 1.22x faster                                  |
| comprehensions           | 17.7 us                                                | 14.7 us: 1.20x faster                                 |
| dulwich_log              | 37.1 ms                                                | 30.8 ms: 1.20x faster                                 |
| scimark_sor              | 127 ms                                                 | 105 ms: 1.20x faster                                  |
| docutils                 | 1.78 sec                                               | 1.50 sec: 1.19x faster                                |
| deepcopy_reduce          | 2.38 us                                                | 2.01 us: 1.19x faster                                 |
| scimark_fft              | 232 ms                                                 | 198 ms: 1.17x faster                                  |
| nqueens                  | 68.1 ms                                                | 58.7 ms: 1.16x faster                                 |
| xml_etree_process        | 45.1 ms                                                | 39.0 ms: 1.15x faster                                 |
| tomli_loads              | 1.76 sec                                               | 1.54 sec: 1.14x faster                                |
| bench_thread_pool        | 548 us                                                 | 480 us: 1.14x faster                                  |
| regex_dna                | 160 ms                                                 | 140 ms: 1.14x faster                                  |
| scimark_sparse_mat_mult  | 3.47 ms                                                | 3.07 ms: 1.13x faster                                 |
| coroutines               | 20.2 ms                                                | 17.9 ms: 1.13x faster                                 |
| sqlglot_optimize         | 38.0 ms                                                | 34.1 ms: 1.11x faster                                 |
| fannkuch                 | 317 ms                                                 | 285 ms: 1.11x faster                                  |
| regex_v8                 | 17.5 ms                                                | 16.3 ms: 1.07x faster                                 |
| meteor_contest           | 78.6 ms                                                | 73.3 ms: 1.07x faster                                 |
| unpickle                 | 9.77 us                                                | 9.17 us: 1.07x faster                                 |
| sqlglot_normalize        | 197 ms                                                 | 187 ms: 1.05x faster                                  |
| python_startup           | 12.6 ms                                                | 12.1 ms: 1.04x faster                                 |
| mdp                      | 1.67 sec                                               | 1.61 sec: 1.04x faster                                |
| python_startup_no_site   | 9.73 ms                                                | 9.49 ms: 1.02x faster                                 |
| pidigits                 | 282 ms                                                 | 282 ms: 1.00x slower                                  |
| gc_traversal             | 2.40 ms                                                | 2.40 ms: 1.00x slower                                 |
| pickle                   | 7.36 us                                                | 7.44 us: 1.01x slower                                 |
| pickle_dict              | 17.8 us                                                | 18.1 us: 1.02x slower                                 |
| xml_etree_parse          | 107 ms                                                 | 110 ms: 1.02x slower                                  |
| regex_effbot             | 2.45 ms                                                | 2.51 ms: 1.03x slower                                 |
| json_loads               | 16.9 us                                                | 17.5 us: 1.04x slower                                 |
| xml_etree_iterparse      | 72.6 ms                                                | 75.4 ms: 1.04x slower                                 |
| xml_etree_generate       | 54.3 ms                                                | 57.2 ms: 1.05x slower                                 |
| sqlite_synth             | 1.47 us                                                | 1.60 us: 1.08x slower                                 |
| bench_mp_pool            | 41.0 ms                                                | 46.6 ms: 1.14x slower                                 |
| pathlib                  | 28.8 ms                                                | 33.0 ms: 1.14x slower                                 |
| coverage                 | 40.8 ms                                                | 46.8 ms: 1.15x slower                                 |
| unpickle_list            | 2.66 us                                                | 3.14 us: 1.18x slower                                 |
| telco                    | 3.68 ms                                                | 4.54 ms: 1.23x slower                                 |
| dask                     | 258 ms                                                 | 333 ms: 1.29x slower                                  |
| async_generators         | 233 ms                                                 | 304 ms: 1.30x slower                                  |
| Geometric mean           | (ref)                                                  | 1.23x faster                                          |

Benchmark hidden because not significant (2): pickle_list, json
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.18x
- 95% likely to have a speedup of 1.16x
- 99% likely to have a speedup of 1.14x
