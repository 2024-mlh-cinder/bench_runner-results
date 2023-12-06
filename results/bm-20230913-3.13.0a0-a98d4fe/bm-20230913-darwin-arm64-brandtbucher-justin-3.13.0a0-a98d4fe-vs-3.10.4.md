
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin
- machine: darwin-arm64
- commit hash: a98d4fe
- commit date: 2023-09-13
- overall geometric mean: 1.21x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.12x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-darwin-arm64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| docutils       | 1.78 sec                                               | 1.53 sec: 1.17x faster                                        |
| tornado_http   | 91.9 ms                                                | 71.9 ms: 1.28x faster                                         |
| Geometric mean | (ref)                                                  | 1.22x faster                                                  |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-darwin-arm64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| float          | 72.3 ms                                                | 56.8 ms: 1.27x faster                                         |
| nbody          | 94.1 ms                                                | 82.4 ms: 1.14x faster                                         |
| pidigits       | 282 ms                                                 | 282 ms: 1.00x slower                                          |
| Geometric mean | (ref)                                                  | 1.13x faster                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-darwin-arm64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_compile  | 96.6 ms                                                | 82.1 ms: 1.18x faster                                         |
| regex_dna      | 160 ms                                                 | 140 ms: 1.14x faster                                          |
| regex_v8       | 17.5 ms                                                | 16.4 ms: 1.07x faster                                         |
| regex_effbot   | 2.45 ms                                                | 2.50 ms: 1.02x slower                                         |
| Geometric mean | (ref)                                                  | 1.09x faster                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-darwin-arm64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| pickle_pure_python   | 284 us                                                 | 196 us: 1.44x faster                                          |
| json_dumps           | 8.38 ms                                                | 6.47 ms: 1.29x faster                                         |
| tomli_loads          | 1.76 sec                                               | 1.41 sec: 1.25x faster                                        |
| unpickle_pure_python | 203 us                                                 | 165 us: 1.24x faster                                          |
| xml_etree_process    | 45.1 ms                                                | 39.4 ms: 1.14x faster                                         |
| unpickle             | 9.77 us                                                | 9.21 us: 1.06x faster                                         |
| pickle_dict          | 17.8 us                                                | 17.9 us: 1.01x slower                                         |
| pickle               | 7.36 us                                                | 7.45 us: 1.01x slower                                         |
| pickle_list          | 2.83 us                                                | 2.87 us: 1.01x slower                                         |
| xml_etree_parse      | 107 ms                                                 | 111 ms: 1.03x slower                                          |
| json_loads           | 16.9 us                                                | 17.5 us: 1.04x slower                                         |
| xml_etree_iterparse  | 72.6 ms                                                | 76.8 ms: 1.06x slower                                         |
| xml_etree_generate   | 54.3 ms                                                | 57.7 ms: 1.06x slower                                         |
| unpickle_list        | 2.66 us                                                | 3.24 us: 1.22x slower                                         |
| Geometric mean       | (ref)                                                  | 1.06x faster                                                  |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-darwin-arm64-brandtbucher-justin-3.13.0a0-a98d4fe |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 12.6 ms                                                | 12.1 ms: 1.04x faster                                         |
| python_startup_no_site | 9.73 ms                                                | 9.45 ms: 1.03x faster                                         |
| Geometric mean         | (ref)                                                  | 1.04x faster                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-darwin-arm64-brandtbucher-justin-3.13.0a0-a98d4fe |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 10.5 ms                                                | 7.67 ms: 1.37x faster                                         |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-darwin-arm64-brandtbucher-justin-3.13.0a0-a98d4fe |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| typing_runtime_protocols | 344 us                                                 | 94.0 us: 3.66x faster                                         |
| deltablue                | 5.15 ms                                                | 2.51 ms: 2.05x faster                                         |
| raytrace                 | 328 ms                                                 | 179 ms: 1.83x faster                                          |
| logging_silent           | 119 ns                                                 | 71.1 ns: 1.67x faster                                         |
| sqlglot_parse            | 1.33 ms                                                | 808 us: 1.65x faster                                          |
| richards_super           | 60.7 ms                                                | 37.7 ms: 1.61x faster                                         |
| async_tree_none          | 402 ms                                                 | 252 ms: 1.59x faster                                          |
| crypto_pyaes             | 78.0 ms                                                | 49.1 ms: 1.59x faster                                         |
| mypy2                    | 308 ms                                                 | 196 ms: 1.57x faster                                          |
| chaos                    | 66.8 ms                                                | 42.5 ms: 1.57x faster                                         |
| scimark_monte_carlo      | 72.2 ms                                                | 46.0 ms: 1.57x faster                                         |
| sqlglot_transpile        | 1.54 ms                                                | 987 us: 1.56x faster                                          |
| asyncio_tcp              | 673 ms                                                 | 441 ms: 1.53x faster                                          |
| go                       | 165 ms                                                 | 109 ms: 1.52x faster                                          |
| scimark_lu               | 110 ms                                                 | 72.7 ms: 1.51x faster                                         |
| richards                 | 51.4 ms                                                | 34.0 ms: 1.51x faster                                         |
| async_tree_memoization   | 493 ms                                                 | 328 ms: 1.50x faster                                          |
| async_tree_io            | 1.02 sec                                               | 697 ms: 1.46x faster                                          |
| pickle_pure_python       | 284 us                                                 | 196 us: 1.44x faster                                          |
| unpack_sequence          | 38.7 ns                                                | 27.0 ns: 1.43x faster                                         |
| mako                     | 10.5 ms                                                | 7.67 ms: 1.37x faster                                         |
| pyflate                  | 453 ms                                                 | 338 ms: 1.34x faster                                          |
| deepcopy_memo            | 34.5 us                                                | 25.9 us: 1.33x faster                                         |
| generators               | 32.9 ms                                                | 24.9 ms: 1.32x faster                                         |
| pycparser                | 915 ms                                                 | 692 ms: 1.32x faster                                          |
| spectral_norm            | 96.4 ms                                                | 73.1 ms: 1.32x faster                                         |
| json_dumps               | 8.38 ms                                                | 6.47 ms: 1.29x faster                                         |
| logging_format           | 5.01 us                                                | 3.87 us: 1.29x faster                                         |
| logging_simple           | 4.63 us                                                | 3.59 us: 1.29x faster                                         |
| asyncio_tcp_ssl          | 1.64 sec                                               | 1.28 sec: 1.29x faster                                        |
| async_tree_cpu_io_mixed  | 670 ms                                                 | 523 ms: 1.28x faster                                          |
| tornado_http             | 91.9 ms                                                | 71.9 ms: 1.28x faster                                         |
| float                    | 72.3 ms                                                | 56.8 ms: 1.27x faster                                         |
| tomli_loads              | 1.76 sec                                               | 1.41 sec: 1.25x faster                                        |
| create_gc_cycles         | 876 us                                                 | 707 us: 1.24x faster                                          |
| unpickle_pure_python     | 203 us                                                 | 165 us: 1.24x faster                                          |
| deepcopy                 | 278 us                                                 | 226 us: 1.23x faster                                          |
| hexiom                   | 6.32 ms                                                | 5.15 ms: 1.23x faster                                         |
| pprint_pformat           | 1.24 sec                                               | 1.03 sec: 1.21x faster                                        |
| pprint_safe_repr         | 609 ms                                                 | 504 ms: 1.21x faster                                          |
| dulwich_log              | 37.1 ms                                                | 30.8 ms: 1.20x faster                                         |
| scimark_sor              | 127 ms                                                 | 106 ms: 1.19x faster                                          |
| deepcopy_reduce          | 2.38 us                                                | 2.02 us: 1.18x faster                                         |
| regex_compile            | 96.6 ms                                                | 82.1 ms: 1.18x faster                                         |
| docutils                 | 1.78 sec                                               | 1.53 sec: 1.17x faster                                        |
| xml_etree_process        | 45.1 ms                                                | 39.4 ms: 1.14x faster                                         |
| nbody                    | 94.1 ms                                                | 82.4 ms: 1.14x faster                                         |
| regex_dna                | 160 ms                                                 | 140 ms: 1.14x faster                                          |
| coroutines               | 20.2 ms                                                | 17.9 ms: 1.13x faster                                         |
| bench_thread_pool        | 548 us                                                 | 492 us: 1.12x faster                                          |
| sqlglot_optimize         | 38.0 ms                                                | 34.6 ms: 1.10x faster                                         |
| fannkuch                 | 317 ms                                                 | 291 ms: 1.09x faster                                          |
| regex_v8                 | 17.5 ms                                                | 16.4 ms: 1.07x faster                                         |
| unpickle                 | 9.77 us                                                | 9.21 us: 1.06x faster                                         |
| sqlglot_normalize        | 197 ms                                                 | 185 ms: 1.06x faster                                          |
| nqueens                  | 68.1 ms                                                | 64.4 ms: 1.06x faster                                         |
| scimark_fft              | 232 ms                                                 | 221 ms: 1.05x faster                                          |
| comprehensions           | 17.7 us                                                | 16.8 us: 1.05x faster                                         |
| python_startup           | 12.6 ms                                                | 12.1 ms: 1.04x faster                                         |
| scimark_sparse_mat_mult  | 3.47 ms                                                | 3.35 ms: 1.04x faster                                         |
| json                     | 3.10 ms                                                | 3.00 ms: 1.03x faster                                         |
| python_startup_no_site   | 9.73 ms                                                | 9.45 ms: 1.03x faster                                         |
| meteor_contest           | 78.6 ms                                                | 77.2 ms: 1.02x faster                                         |
| pidigits                 | 282 ms                                                 | 282 ms: 1.00x slower                                          |
| gc_traversal             | 2.40 ms                                                | 2.41 ms: 1.00x slower                                         |
| pickle_dict              | 17.8 us                                                | 17.9 us: 1.01x slower                                         |
| pickle                   | 7.36 us                                                | 7.45 us: 1.01x slower                                         |
| pickle_list              | 2.83 us                                                | 2.87 us: 1.01x slower                                         |
| regex_effbot             | 2.45 ms                                                | 2.50 ms: 1.02x slower                                         |
| xml_etree_parse          | 107 ms                                                 | 111 ms: 1.03x slower                                          |
| json_loads               | 16.9 us                                                | 17.5 us: 1.04x slower                                         |
| xml_etree_iterparse      | 72.6 ms                                                | 76.8 ms: 1.06x slower                                         |
| xml_etree_generate       | 54.3 ms                                                | 57.7 ms: 1.06x slower                                         |
| sqlite_synth             | 1.47 us                                                | 1.60 us: 1.08x slower                                         |
| pathlib                  | 28.8 ms                                                | 32.5 ms: 1.13x slower                                         |
| coverage                 | 40.8 ms                                                | 47.0 ms: 1.15x slower                                         |
| bench_mp_pool            | 41.0 ms                                                | 47.6 ms: 1.16x slower                                         |
| unpickle_list            | 2.66 us                                                | 3.24 us: 1.22x slower                                         |
| telco                    | 3.68 ms                                                | 4.71 ms: 1.28x slower                                         |
| dask                     | 258 ms                                                 | 333 ms: 1.29x slower                                          |
| async_generators         | 233 ms                                                 | 311 ms: 1.33x slower                                          |
| Geometric mean           | (ref)                                                  | 1.21x faster                                                  |

Benchmark hidden because not significant (1): mdp
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.16x
- 95% likely to have a speedup of 1.14x
- 99% likely to have a speedup of 1.12x
