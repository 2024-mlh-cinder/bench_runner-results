
# Results vs. 3.10.4

- fork: faster-cpython
- ref: no_deep_freeze_3
- machine: darwin-arm64
- commit hash: 0bed3bc
- commit date: 2023-08-28
- overall geometric mean: 1.21x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.13x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230828-darwin-arm64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| docutils       | 1.78 sec                                               | 1.52 sec: 1.18x faster                                                      |
| tornado_http   | 91.9 ms                                                | 71.8 ms: 1.28x faster                                                       |
| Geometric mean | (ref)                                                  | 1.23x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230828-darwin-arm64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| nbody          | 94.1 ms                                                | 72.0 ms: 1.31x faster                                                       |
| float          | 72.3 ms                                                | 56.7 ms: 1.28x faster                                                       |
| Geometric mean | (ref)                                                  | 1.19x faster                                                                |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230828-darwin-arm64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 96.6 ms                                                | 79.1 ms: 1.22x faster                                                       |
| regex_dna      | 160 ms                                                 | 149 ms: 1.07x faster                                                        |
| regex_v8       | 17.5 ms                                                | 17.0 ms: 1.03x faster                                                       |
| regex_effbot   | 2.45 ms                                                | 2.58 ms: 1.05x slower                                                       |
| Geometric mean | (ref)                                                  | 1.06x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230828-darwin-arm64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_pure_python   | 284 us                                                 | 200 us: 1.42x faster                                                        |
| json_dumps           | 8.38 ms                                                | 6.49 ms: 1.29x faster                                                       |
| unpickle_pure_python | 203 us                                                 | 162 us: 1.26x faster                                                        |
| tomli_loads          | 1.76 sec                                               | 1.55 sec: 1.14x faster                                                      |
| xml_etree_process    | 45.1 ms                                                | 40.8 ms: 1.10x faster                                                       |
| unpickle             | 9.77 us                                                | 9.11 us: 1.07x faster                                                       |
| pickle               | 7.36 us                                                | 7.41 us: 1.01x slower                                                       |
| pickle_dict          | 17.8 us                                                | 17.9 us: 1.01x slower                                                       |
| pickle_list          | 2.83 us                                                | 2.86 us: 1.01x slower                                                       |
| xml_etree_parse      | 107 ms                                                 | 110 ms: 1.02x slower                                                        |
| json_loads           | 16.9 us                                                | 17.5 us: 1.03x slower                                                       |
| xml_etree_iterparse  | 72.6 ms                                                | 76.1 ms: 1.05x slower                                                       |
| xml_etree_generate   | 54.3 ms                                                | 58.8 ms: 1.08x slower                                                       |
| unpickle_list        | 2.66 us                                                | 3.18 us: 1.19x slower                                                       |
| Geometric mean       | (ref)                                                  | 1.05x faster                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230828-darwin-arm64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 12.6 ms                                                | 11.8 ms: 1.07x faster                                                       |
| python_startup_no_site | 9.73 ms                                                | 9.15 ms: 1.06x faster                                                       |
| Geometric mean         | (ref)                                                  | 1.07x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230828-darwin-arm64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 10.5 ms                                                | 7.43 ms: 1.41x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230828-darwin-arm64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 344 us                                                 | 94.0 us: 3.66x faster                                                       |
| deltablue                | 5.15 ms                                                | 2.55 ms: 2.02x faster                                                       |
| raytrace                 | 328 ms                                                 | 189 ms: 1.73x faster                                                        |
| crypto_pyaes             | 78.0 ms                                                | 47.7 ms: 1.63x faster                                                       |
| sqlglot_parse            | 1.33 ms                                                | 832 us: 1.60x faster                                                        |
| chaos                    | 66.8 ms                                                | 41.9 ms: 1.60x faster                                                       |
| mypy2                    | 308 ms                                                 | 193 ms: 1.60x faster                                                        |
| logging_silent           | 119 ns                                                 | 75.6 ns: 1.57x faster                                                       |
| async_tree_none          | 402 ms                                                 | 256 ms: 1.57x faster                                                        |
| richards_super           | 60.7 ms                                                | 38.7 ms: 1.57x faster                                                       |
| scimark_monte_carlo      | 72.2 ms                                                | 46.2 ms: 1.56x faster                                                       |
| asyncio_tcp              | 673 ms                                                 | 439 ms: 1.53x faster                                                        |
| sqlglot_transpile        | 1.54 ms                                                | 1.01 ms: 1.52x faster                                                       |
| go                       | 165 ms                                                 | 109 ms: 1.51x faster                                                        |
| async_tree_memoization   | 493 ms                                                 | 331 ms: 1.49x faster                                                        |
| richards                 | 51.4 ms                                                | 35.5 ms: 1.45x faster                                                       |
| async_tree_io            | 1.02 sec                                               | 704 ms: 1.45x faster                                                        |
| scimark_lu               | 110 ms                                                 | 76.2 ms: 1.44x faster                                                       |
| pickle_pure_python       | 284 us                                                 | 200 us: 1.42x faster                                                        |
| mako                     | 10.5 ms                                                | 7.43 ms: 1.41x faster                                                       |
| unpack_sequence          | 38.7 ns                                                | 27.9 ns: 1.39x faster                                                       |
| deepcopy_memo            | 34.5 us                                                | 25.0 us: 1.38x faster                                                       |
| nbody                    | 94.1 ms                                                | 72.0 ms: 1.31x faster                                                       |
| pycparser                | 915 ms                                                 | 701 ms: 1.31x faster                                                        |
| pyflate                  | 453 ms                                                 | 348 ms: 1.30x faster                                                        |
| spectral_norm            | 96.4 ms                                                | 74.0 ms: 1.30x faster                                                       |
| hexiom                   | 6.32 ms                                                | 4.86 ms: 1.30x faster                                                       |
| json_dumps               | 8.38 ms                                                | 6.49 ms: 1.29x faster                                                       |
| asyncio_tcp_ssl          | 1.64 sec                                               | 1.27 sec: 1.29x faster                                                      |
| tornado_http             | 91.9 ms                                                | 71.8 ms: 1.28x faster                                                       |
| float                    | 72.3 ms                                                | 56.7 ms: 1.28x faster                                                       |
| async_tree_cpu_io_mixed  | 670 ms                                                 | 526 ms: 1.27x faster                                                        |
| generators               | 32.9 ms                                                | 26.2 ms: 1.26x faster                                                       |
| logging_format           | 5.01 us                                                | 3.99 us: 1.26x faster                                                       |
| unpickle_pure_python     | 203 us                                                 | 162 us: 1.26x faster                                                        |
| create_gc_cycles         | 876 us                                                 | 708 us: 1.24x faster                                                        |
| logging_simple           | 4.63 us                                                | 3.74 us: 1.24x faster                                                       |
| regex_compile            | 96.6 ms                                                | 79.1 ms: 1.22x faster                                                       |
| dulwich_log              | 37.1 ms                                                | 30.9 ms: 1.20x faster                                                       |
| deepcopy                 | 278 us                                                 | 231 us: 1.20x faster                                                        |
| pprint_safe_repr         | 609 ms                                                 | 512 ms: 1.19x faster                                                        |
| pprint_pformat           | 1.24 sec                                               | 1.04 sec: 1.19x faster                                                      |
| comprehensions           | 17.7 us                                                | 14.9 us: 1.18x faster                                                       |
| docutils                 | 1.78 sec                                               | 1.52 sec: 1.18x faster                                                      |
| scimark_sor              | 127 ms                                                 | 108 ms: 1.17x faster                                                        |
| scimark_fft              | 232 ms                                                 | 201 ms: 1.15x faster                                                        |
| nqueens                  | 68.1 ms                                                | 59.2 ms: 1.15x faster                                                       |
| deepcopy_reduce          | 2.38 us                                                | 2.09 us: 1.14x faster                                                       |
| tomli_loads              | 1.76 sec                                               | 1.55 sec: 1.14x faster                                                      |
| scimark_sparse_mat_mult  | 3.47 ms                                                | 3.09 ms: 1.12x faster                                                       |
| bench_thread_pool        | 548 us                                                 | 490 us: 1.12x faster                                                        |
| fannkuch                 | 317 ms                                                 | 287 ms: 1.11x faster                                                        |
| xml_etree_process        | 45.1 ms                                                | 40.8 ms: 1.10x faster                                                       |
| sqlglot_optimize         | 38.0 ms                                                | 35.1 ms: 1.08x faster                                                       |
| coroutines               | 20.2 ms                                                | 18.8 ms: 1.07x faster                                                       |
| unpickle                 | 9.77 us                                                | 9.11 us: 1.07x faster                                                       |
| regex_dna                | 160 ms                                                 | 149 ms: 1.07x faster                                                        |
| python_startup           | 12.6 ms                                                | 11.8 ms: 1.07x faster                                                       |
| python_startup_no_site   | 9.73 ms                                                | 9.15 ms: 1.06x faster                                                       |
| meteor_contest           | 78.6 ms                                                | 74.1 ms: 1.06x faster                                                       |
| regex_v8                 | 17.5 ms                                                | 17.0 ms: 1.03x faster                                                       |
| sqlglot_normalize        | 197 ms                                                 | 191 ms: 1.03x faster                                                        |
| json                     | 3.10 ms                                                | 3.01 ms: 1.03x faster                                                       |
| mdp                      | 1.67 sec                                               | 1.64 sec: 1.02x faster                                                      |
| gc_traversal             | 2.40 ms                                                | 2.40 ms: 1.00x slower                                                       |
| pickle                   | 7.36 us                                                | 7.41 us: 1.01x slower                                                       |
| pickle_dict              | 17.8 us                                                | 17.9 us: 1.01x slower                                                       |
| pickle_list              | 2.83 us                                                | 2.86 us: 1.01x slower                                                       |
| xml_etree_parse          | 107 ms                                                 | 110 ms: 1.02x slower                                                        |
| json_loads               | 16.9 us                                                | 17.5 us: 1.03x slower                                                       |
| xml_etree_iterparse      | 72.6 ms                                                | 76.1 ms: 1.05x slower                                                       |
| regex_effbot             | 2.45 ms                                                | 2.58 ms: 1.05x slower                                                       |
| xml_etree_generate       | 54.3 ms                                                | 58.8 ms: 1.08x slower                                                       |
| sqlite_synth             | 1.47 us                                                | 1.60 us: 1.09x slower                                                       |
| pathlib                  | 28.8 ms                                                | 32.4 ms: 1.12x slower                                                       |
| bench_mp_pool            | 41.0 ms                                                | 46.4 ms: 1.13x slower                                                       |
| coverage                 | 40.8 ms                                                | 47.3 ms: 1.16x slower                                                       |
| unpickle_list            | 2.66 us                                                | 3.18 us: 1.19x slower                                                       |
| telco                    | 3.68 ms                                                | 4.57 ms: 1.24x slower                                                       |
| dask                     | 258 ms                                                 | 337 ms: 1.31x slower                                                        |
| async_generators         | 233 ms                                                 | 309 ms: 1.32x slower                                                        |
| Geometric mean           | (ref)                                                  | 1.21x faster                                                                |

Benchmark hidden because not significant (1): pidigits
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.16x
- 95% likely to have a speedup of 1.15x
- 99% likely to have a speedup of 1.13x
