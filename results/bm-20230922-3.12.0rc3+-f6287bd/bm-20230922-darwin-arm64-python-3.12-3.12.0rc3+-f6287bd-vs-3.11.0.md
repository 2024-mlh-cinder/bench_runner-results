
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: darwin-arm64
- commit hash: f6287bd
- commit date: 2023-09-22
- overall geometric mean: 1.01x faster
- HPT reliability: 62.09%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230922-darwin-arm64-python-3.12-3.12.0rc3+-f6287bd |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| 2to3           | 161 ms                                                 | 170 ms: 1.05x slower                                    |
| docutils       | 1.47 sec                                               | 1.53 sec: 1.04x slower                                  |
| Geometric mean | (ref)                                                  | 1.03x slower                                            |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230922-darwin-arm64-python-3.12-3.12.0rc3+-f6287bd |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| pidigits       | 281 ms                                                 | 282 ms: 1.00x slower                                    |
| nbody          | 65.6 ms                                                | 68.5 ms: 1.04x slower                                   |
| float          | 53.0 ms                                                | 57.9 ms: 1.09x slower                                   |
| Geometric mean | (ref)                                                  | 1.05x slower                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230922-darwin-arm64-python-3.12-3.12.0rc3+-f6287bd |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_v8       | 16.1 ms                                                | 15.6 ms: 1.04x faster                                   |
| regex_effbot   | 2.63 ms                                                | 2.56 ms: 1.03x faster                                   |
| regex_compile  | 76.7 ms                                                | 75.6 ms: 1.02x faster                                   |
| regex_dna      | 152 ms                                                 | 150 ms: 1.01x faster                                    |
| Geometric mean | (ref)                                                  | 1.02x faster                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230922-darwin-arm64-python-3.12-3.12.0rc3+-f6287bd |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| json_dumps           | 7.63 ms                                                | 6.45 ms: 1.18x faster                                   |
| unpickle_pure_python | 159 us                                                 | 144 us: 1.11x faster                                    |
| pickle_pure_python   | 201 us                                                 | 188 us: 1.07x faster                                    |
| tomli_loads          | 1.47 sec                                               | 1.38 sec: 1.06x faster                                  |
| unpickle             | 9.67 us                                                | 9.19 us: 1.05x faster                                   |
| pickle_list          | 2.81 us                                                | 2.90 us: 1.03x slower                                   |
| pickle               | 7.15 us                                                | 7.45 us: 1.04x slower                                   |
| xml_etree_iterparse  | 70.1 ms                                                | 73.9 ms: 1.05x slower                                   |
| json_loads           | 16.1 us                                                | 17.6 us: 1.09x slower                                   |
| xml_etree_process    | 35.1 ms                                                | 38.5 ms: 1.10x slower                                   |
| xml_etree_generate   | 48.3 ms                                                | 55.7 ms: 1.16x slower                                   |
| unpickle_list        | 2.65 us                                                | 3.21 us: 1.21x slower                                   |
| Geometric mean       | (ref)                                                  | 1.01x slower                                            |

Benchmark hidden because not significant (2): xml_etree_parse, pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230922-darwin-arm64-python-3.12-3.12.0rc3+-f6287bd |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| python_startup         | 12.4 ms                                                | 11.9 ms: 1.05x faster                                   |
| python_startup_no_site | 10.2 ms                                                | 9.73 ms: 1.04x faster                                   |
| Geometric mean         | (ref)                                                  | 1.05x faster                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230922-darwin-arm64-python-3.12-3.12.0rc3+-f6287bd |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------:|
| mako      | 8.53 ms                                                | 7.52 ms: 1.13x faster                                   |

All benchmarks:
===============

| Benchmark                | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230922-darwin-arm64-python-3.12-3.12.0rc3+-f6287bd |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 90.5 us: 3.71x faster                                   |
| asyncio_tcp              | 651 ms                                                 | 454 ms: 1.43x faster                                    |
| unpack_sequence          | 34.1 ns                                                | 28.7 ns: 1.19x faster                                   |
| json_dumps               | 7.63 ms                                                | 6.45 ms: 1.18x faster                                   |
| asyncio_tcp_ssl          | 1.44 sec                                               | 1.25 sec: 1.16x faster                                  |
| coverage                 | 58.4 ms                                                | 51.4 ms: 1.14x faster                                   |
| mako                     | 8.53 ms                                                | 7.52 ms: 1.13x faster                                   |
| richards_super           | 39.2 ms                                                | 34.9 ms: 1.12x faster                                   |
| unpickle_pure_python     | 159 us                                                 | 144 us: 1.11x faster                                    |
| async_tree_none          | 286 ms                                                 | 259 ms: 1.10x faster                                    |
| async_tree_memoization   | 336 ms                                                 | 306 ms: 1.10x faster                                    |
| hexiom                   | 4.72 ms                                                | 4.31 ms: 1.10x faster                                   |
| chaos                    | 49.4 ms                                                | 45.2 ms: 1.09x faster                                   |
| deltablue                | 2.81 ms                                                | 2.59 ms: 1.09x faster                                   |
| deepcopy_memo            | 26.3 us                                                | 24.5 us: 1.07x faster                                   |
| sqlglot_parse            | 959 us                                                 | 896 us: 1.07x faster                                    |
| pickle_pure_python       | 201 us                                                 | 188 us: 1.07x faster                                    |
| async_tree_io            | 704 ms                                                 | 660 ms: 1.07x faster                                    |
| tomli_loads              | 1.47 sec                                               | 1.38 sec: 1.06x faster                                  |
| unpickle                 | 9.67 us                                                | 9.19 us: 1.05x faster                                   |
| pycparser                | 698 ms                                                 | 664 ms: 1.05x faster                                    |
| python_startup           | 12.4 ms                                                | 11.9 ms: 1.05x faster                                   |
| sqlglot_transpile        | 1.12 ms                                                | 1.07 ms: 1.05x faster                                   |
| python_startup_no_site   | 10.2 ms                                                | 9.73 ms: 1.04x faster                                   |
| richards                 | 32.2 ms                                                | 31.1 ms: 1.04x faster                                   |
| regex_v8                 | 16.1 ms                                                | 15.6 ms: 1.04x faster                                   |
| regex_effbot             | 2.63 ms                                                | 2.56 ms: 1.03x faster                                   |
| comprehensions           | 16.1 us                                                | 15.7 us: 1.03x faster                                   |
| async_tree_cpu_io_mixed  | 533 ms                                                 | 521 ms: 1.02x faster                                    |
| scimark_lu               | 73.3 ms                                                | 71.7 ms: 1.02x faster                                   |
| sqlalchemy_imperative    | 7.20 ms                                                | 7.05 ms: 1.02x faster                                   |
| scimark_sparse_mat_mult  | 3.19 ms                                                | 3.14 ms: 1.02x faster                                   |
| regex_compile            | 76.7 ms                                                | 75.6 ms: 1.02x faster                                   |
| regex_dna                | 152 ms                                                 | 150 ms: 1.01x faster                                    |
| create_gc_cycles         | 716 us                                                 | 706 us: 1.01x faster                                    |
| generators               | 28.8 ms                                                | 28.4 ms: 1.01x faster                                   |
| scimark_fft              | 200 ms                                                 | 198 ms: 1.01x faster                                    |
| logging_silent           | 68.1 ns                                                | 67.5 ns: 1.01x faster                                   |
| gc_traversal             | 2.42 ms                                                | 2.40 ms: 1.01x faster                                   |
| meteor_contest           | 73.5 ms                                                | 73.2 ms: 1.00x faster                                   |
| pidigits                 | 281 ms                                                 | 282 ms: 1.00x slower                                    |
| deepcopy                 | 223 us                                                 | 224 us: 1.00x slower                                    |
| crypto_pyaes             | 51.7 ms                                                | 52.2 ms: 1.01x slower                                   |
| nqueens                  | 59.8 ms                                                | 60.3 ms: 1.01x slower                                   |
| coroutines               | 17.8 ms                                                | 18.1 ms: 1.02x slower                                   |
| fannkuch                 | 261 ms                                                 | 268 ms: 1.02x slower                                    |
| bench_thread_pool        | 474 us                                                 | 488 us: 1.03x slower                                    |
| spectral_norm            | 72.6 ms                                                | 74.8 ms: 1.03x slower                                   |
| pickle_list              | 2.81 us                                                | 2.90 us: 1.03x slower                                   |
| sqlalchemy_declarative   | 62.6 ms                                                | 64.8 ms: 1.04x slower                                   |
| logging_simple           | 3.55 us                                                | 3.68 us: 1.04x slower                                   |
| docutils                 | 1.47 sec                                               | 1.53 sec: 1.04x slower                                  |
| pickle                   | 7.15 us                                                | 7.45 us: 1.04x slower                                   |
| nbody                    | 65.6 ms                                                | 68.5 ms: 1.04x slower                                   |
| pprint_pformat           | 954 ms                                                 | 1.00 sec: 1.05x slower                                  |
| logging_format           | 3.78 us                                                | 3.97 us: 1.05x slower                                   |
| 2to3                     | 161 ms                                                 | 170 ms: 1.05x slower                                    |
| xml_etree_iterparse      | 70.1 ms                                                | 73.9 ms: 1.05x slower                                   |
| pprint_safe_repr         | 466 ms                                                 | 492 ms: 1.05x slower                                    |
| pyflate                  | 310 ms                                                 | 327 ms: 1.06x slower                                    |
| bench_mp_pool            | 43.9 ms                                                | 46.4 ms: 1.06x slower                                   |
| deepcopy_reduce          | 1.91 us                                                | 2.02 us: 1.06x slower                                   |
| mdp                      | 1.55 sec                                               | 1.66 sec: 1.07x slower                                  |
| scimark_monte_carlo      | 46.5 ms                                                | 50.0 ms: 1.08x slower                                   |
| sqlglot_normalize        | 171 ms                                                 | 186 ms: 1.09x slower                                    |
| telco                    | 3.41 ms                                                | 3.72 ms: 1.09x slower                                   |
| json_loads               | 16.1 us                                                | 17.6 us: 1.09x slower                                   |
| float                    | 53.0 ms                                                | 57.9 ms: 1.09x slower                                   |
| xml_etree_process        | 35.1 ms                                                | 38.5 ms: 1.10x slower                                   |
| sqlglot_optimize         | 31.1 ms                                                | 34.2 ms: 1.10x slower                                   |
| json                     | 2.78 ms                                                | 3.06 ms: 1.10x slower                                   |
| scimark_sor              | 82.6 ms                                                | 94.2 ms: 1.14x slower                                   |
| xml_etree_generate       | 48.3 ms                                                | 55.7 ms: 1.16x slower                                   |
| raytrace                 | 207 ms                                                 | 245 ms: 1.18x slower                                    |
| pathlib                  | 27.2 ms                                                | 32.8 ms: 1.21x slower                                   |
| unpickle_list            | 2.65 us                                                | 3.21 us: 1.21x slower                                   |
| sqlite_synth             | 1.27 us                                                | 1.60 us: 1.26x slower                                   |
| mypy2                    | 195 ms                                                 | 256 ms: 1.31x slower                                    |
| async_generators         | 196 ms                                                 | 304 ms: 1.55x slower                                    |
| Geometric mean           | (ref)                                                  | 1.01x faster                                            |

Benchmark hidden because not significant (5): xml_etree_parse, go, pickle_dict, dulwich_log, tornado_http
Ignored benchmarks (14) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
Ignored benchmarks (1) of results/bm-20230922-3.12.0rc3+-f6287bd/bm-20230922-darwin-arm64-python-3.12-3.12.0rc3+-f6287bd.json: dask


# HPT report

- Reliability score: 62.09% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
