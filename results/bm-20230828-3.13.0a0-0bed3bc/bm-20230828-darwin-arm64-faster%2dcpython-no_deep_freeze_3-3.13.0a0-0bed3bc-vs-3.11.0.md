
# Results vs. 3.11.0

- fork: faster-cpython
- ref: no_deep_freeze_3
- machine: darwin-arm64
- commit hash: 0bed3bc
- commit date: 2023-08-28
- overall geometric mean: 1.00x slower
- HPT reliability: 99.02%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230828-darwin-arm64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| docutils       | 1.47 sec                                               | 1.52 sec: 1.03x slower                                                      |
| Geometric mean | (ref)                                                  | 1.02x slower                                                                |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230828-darwin-arm64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 281 ms                                                 | 282 ms: 1.00x slower                                                        |
| float          | 53.0 ms                                                | 56.7 ms: 1.07x slower                                                       |
| nbody          | 65.6 ms                                                | 72.0 ms: 1.10x slower                                                       |
| Geometric mean | (ref)                                                  | 1.06x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230828-darwin-arm64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_effbot   | 2.63 ms                                                | 2.58 ms: 1.02x faster                                                       |
| regex_dna      | 152 ms                                                 | 149 ms: 1.02x faster                                                        |
| regex_compile  | 76.7 ms                                                | 79.1 ms: 1.03x slower                                                       |
| regex_v8       | 16.1 ms                                                | 17.0 ms: 1.06x slower                                                       |
| Geometric mean | (ref)                                                  | 1.01x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230828-darwin-arm64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 7.63 ms                                                | 6.49 ms: 1.18x faster                                                       |
| unpickle             | 9.67 us                                                | 9.11 us: 1.06x faster                                                       |
| xml_etree_parse      | 108 ms                                                 | 110 ms: 1.01x slower                                                        |
| pickle_list          | 2.81 us                                                | 2.86 us: 1.02x slower                                                       |
| unpickle_pure_python | 159 us                                                 | 162 us: 1.02x slower                                                        |
| pickle               | 7.15 us                                                | 7.41 us: 1.04x slower                                                       |
| tomli_loads          | 1.47 sec                                               | 1.55 sec: 1.06x slower                                                      |
| xml_etree_iterparse  | 70.1 ms                                                | 76.1 ms: 1.08x slower                                                       |
| json_loads           | 16.1 us                                                | 17.5 us: 1.09x slower                                                       |
| xml_etree_process    | 35.1 ms                                                | 40.8 ms: 1.16x slower                                                       |
| unpickle_list        | 2.65 us                                                | 3.18 us: 1.20x slower                                                       |
| xml_etree_generate   | 48.3 ms                                                | 58.8 ms: 1.22x slower                                                       |
| Geometric mean       | (ref)                                                  | 1.04x slower                                                                |

Benchmark hidden because not significant (2): pickle_dict, pickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230828-darwin-arm64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 10.2 ms                                                | 9.15 ms: 1.11x faster                                                       |
| python_startup         | 12.4 ms                                                | 11.8 ms: 1.05x faster                                                       |
| Geometric mean         | (ref)                                                  | 1.08x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230828-darwin-arm64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 8.53 ms                                                | 7.43 ms: 1.15x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230828-darwin-arm64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 94.0 us: 3.57x faster                                                       |
| asyncio_tcp              | 651 ms                                                 | 439 ms: 1.48x faster                                                        |
| coverage                 | 58.4 ms                                                | 47.3 ms: 1.24x faster                                                       |
| unpack_sequence          | 34.1 ns                                                | 27.9 ns: 1.22x faster                                                       |
| chaos                    | 49.4 ms                                                | 41.9 ms: 1.18x faster                                                       |
| json_dumps               | 7.63 ms                                                | 6.49 ms: 1.18x faster                                                       |
| sqlglot_parse            | 959 us                                                 | 832 us: 1.15x faster                                                        |
| mako                     | 8.53 ms                                                | 7.43 ms: 1.15x faster                                                       |
| asyncio_tcp_ssl          | 1.44 sec                                               | 1.27 sec: 1.13x faster                                                      |
| async_tree_none          | 286 ms                                                 | 256 ms: 1.12x faster                                                        |
| sqlglot_transpile        | 1.12 ms                                                | 1.01 ms: 1.11x faster                                                       |
| python_startup_no_site   | 10.2 ms                                                | 9.15 ms: 1.11x faster                                                       |
| deltablue                | 2.81 ms                                                | 2.55 ms: 1.10x faster                                                       |
| generators               | 28.8 ms                                                | 26.2 ms: 1.10x faster                                                       |
| raytrace                 | 207 ms                                                 | 189 ms: 1.09x faster                                                        |
| crypto_pyaes             | 51.7 ms                                                | 47.7 ms: 1.08x faster                                                       |
| comprehensions           | 16.1 us                                                | 14.9 us: 1.08x faster                                                       |
| unpickle                 | 9.67 us                                                | 9.11 us: 1.06x faster                                                       |
| python_startup           | 12.4 ms                                                | 11.8 ms: 1.05x faster                                                       |
| deepcopy_memo            | 26.3 us                                                | 25.0 us: 1.05x faster                                                       |
| scimark_sparse_mat_mult  | 3.19 ms                                                | 3.09 ms: 1.03x faster                                                       |
| regex_effbot             | 2.63 ms                                                | 2.58 ms: 1.02x faster                                                       |
| regex_dna                | 152 ms                                                 | 149 ms: 1.02x faster                                                        |
| richards_super           | 39.2 ms                                                | 38.7 ms: 1.01x faster                                                       |
| async_tree_cpu_io_mixed  | 533 ms                                                 | 526 ms: 1.01x faster                                                        |
| create_gc_cycles         | 716 us                                                 | 708 us: 1.01x faster                                                        |
| nqueens                  | 59.8 ms                                                | 59.2 ms: 1.01x faster                                                       |
| mypy2                    | 195 ms                                                 | 193 ms: 1.01x faster                                                        |
| scimark_monte_carlo      | 46.5 ms                                                | 46.2 ms: 1.01x faster                                                       |
| gc_traversal             | 2.42 ms                                                | 2.40 ms: 1.00x faster                                                       |
| go                       | 109 ms                                                 | 109 ms: 1.00x slower                                                        |
| pidigits                 | 281 ms                                                 | 282 ms: 1.00x slower                                                        |
| meteor_contest           | 73.5 ms                                                | 74.1 ms: 1.01x slower                                                       |
| scimark_fft              | 200 ms                                                 | 201 ms: 1.01x slower                                                        |
| xml_etree_parse          | 108 ms                                                 | 110 ms: 1.01x slower                                                        |
| pickle_list              | 2.81 us                                                | 2.86 us: 1.02x slower                                                       |
| unpickle_pure_python     | 159 us                                                 | 162 us: 1.02x slower                                                        |
| dulwich_log              | 30.3 ms                                                | 30.9 ms: 1.02x slower                                                       |
| spectral_norm            | 72.6 ms                                                | 74.0 ms: 1.02x slower                                                       |
| hexiom                   | 4.72 ms                                                | 4.86 ms: 1.03x slower                                                       |
| regex_compile            | 76.7 ms                                                | 79.1 ms: 1.03x slower                                                       |
| docutils                 | 1.47 sec                                               | 1.52 sec: 1.03x slower                                                      |
| bench_thread_pool        | 474 us                                                 | 490 us: 1.03x slower                                                        |
| pickle                   | 7.15 us                                                | 7.41 us: 1.04x slower                                                       |
| scimark_lu               | 73.3 ms                                                | 76.2 ms: 1.04x slower                                                       |
| deepcopy                 | 223 us                                                 | 231 us: 1.04x slower                                                        |
| logging_simple           | 3.55 us                                                | 3.74 us: 1.05x slower                                                       |
| logging_format           | 3.78 us                                                | 3.99 us: 1.06x slower                                                       |
| bench_mp_pool            | 43.9 ms                                                | 46.4 ms: 1.06x slower                                                       |
| regex_v8                 | 16.1 ms                                                | 17.0 ms: 1.06x slower                                                       |
| coroutines               | 17.8 ms                                                | 18.8 ms: 1.06x slower                                                       |
| tomli_loads              | 1.47 sec                                               | 1.55 sec: 1.06x slower                                                      |
| mdp                      | 1.55 sec                                               | 1.64 sec: 1.06x slower                                                      |
| float                    | 53.0 ms                                                | 56.7 ms: 1.07x slower                                                       |
| json                     | 2.78 ms                                                | 3.01 ms: 1.08x slower                                                       |
| xml_etree_iterparse      | 70.1 ms                                                | 76.1 ms: 1.08x slower                                                       |
| json_loads               | 16.1 us                                                | 17.5 us: 1.09x slower                                                       |
| deepcopy_reduce          | 1.91 us                                                | 2.09 us: 1.09x slower                                                       |
| pprint_pformat           | 954 ms                                                 | 1.04 sec: 1.09x slower                                                      |
| pprint_safe_repr         | 466 ms                                                 | 512 ms: 1.10x slower                                                        |
| fannkuch                 | 261 ms                                                 | 287 ms: 1.10x slower                                                        |
| nbody                    | 65.6 ms                                                | 72.0 ms: 1.10x slower                                                       |
| richards                 | 32.2 ms                                                | 35.5 ms: 1.10x slower                                                       |
| logging_silent           | 68.1 ns                                                | 75.6 ns: 1.11x slower                                                       |
| sqlglot_normalize        | 171 ms                                                 | 191 ms: 1.12x slower                                                        |
| pyflate                  | 310 ms                                                 | 348 ms: 1.12x slower                                                        |
| sqlglot_optimize         | 31.1 ms                                                | 35.1 ms: 1.13x slower                                                       |
| xml_etree_process        | 35.1 ms                                                | 40.8 ms: 1.16x slower                                                       |
| pathlib                  | 27.2 ms                                                | 32.4 ms: 1.19x slower                                                       |
| unpickle_list            | 2.65 us                                                | 3.18 us: 1.20x slower                                                       |
| xml_etree_generate       | 48.3 ms                                                | 58.8 ms: 1.22x slower                                                       |
| sqlite_synth             | 1.27 us                                                | 1.60 us: 1.26x slower                                                       |
| scimark_sor              | 82.6 ms                                                | 108 ms: 1.31x slower                                                        |
| telco                    | 3.41 ms                                                | 4.57 ms: 1.34x slower                                                       |
| async_generators         | 196 ms                                                 | 309 ms: 1.57x slower                                                        |
| Geometric mean           | (ref)                                                  | 1.00x slower                                                                |

Benchmark hidden because not significant (6): async_tree_memoization, pickle_dict, pickle_pure_python, async_tree_io, tornado_http, pycparser
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
Ignored benchmarks (1) of results/bm-20230828-3.13.0a0-0bed3bc/bm-20230828-darwin-arm64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc.json: dask


# HPT report

- Reliability score: 99.02% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
