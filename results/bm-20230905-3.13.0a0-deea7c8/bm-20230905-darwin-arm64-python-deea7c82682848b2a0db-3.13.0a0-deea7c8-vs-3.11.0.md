
# Results vs. 3.11.0

- fork: python
- ref: deea7c82682848b2a0db
- machine: darwin-arm64
- commit hash: deea7c8
- commit date: 2023-09-05
- overall geometric mean: 1.01x faster
- HPT reliability: 66.50%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| docutils       | 1.47 sec                                               | 1.49 sec: 1.01x slower                                                |
| Geometric mean | (ref)                                                  | 1.01x faster                                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pidigits       | 281 ms                                                 | 282 ms: 1.00x slower                                                  |
| float          | 53.0 ms                                                | 55.4 ms: 1.05x slower                                                 |
| nbody          | 65.6 ms                                                | 71.2 ms: 1.09x slower                                                 |
| Geometric mean | (ref)                                                  | 1.05x slower                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_dna      | 152 ms                                                 | 140 ms: 1.08x faster                                                  |
| regex_effbot   | 2.63 ms                                                | 2.50 ms: 1.05x faster                                                 |
| regex_v8       | 16.1 ms                                                | 16.2 ms: 1.00x slower                                                 |
| regex_compile  | 76.7 ms                                                | 77.2 ms: 1.01x slower                                                 |
| Geometric mean | (ref)                                                  | 1.03x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| json_dumps           | 7.63 ms                                                | 6.41 ms: 1.19x faster                                                 |
| unpickle             | 9.67 us                                                | 9.13 us: 1.06x faster                                                 |
| pickle_pure_python   | 201 us                                                 | 193 us: 1.04x faster                                                  |
| unpickle_pure_python | 159 us                                                 | 158 us: 1.01x faster                                                  |
| pickle_dict          | 18.0 us                                                | 18.1 us: 1.01x slower                                                 |
| xml_etree_parse      | 108 ms                                                 | 110 ms: 1.01x slower                                                  |
| pickle_list          | 2.81 us                                                | 2.86 us: 1.02x slower                                                 |
| pickle               | 7.15 us                                                | 7.46 us: 1.04x slower                                                 |
| tomli_loads          | 1.47 sec                                               | 1.54 sec: 1.05x slower                                                |
| xml_etree_iterparse  | 70.1 ms                                                | 75.3 ms: 1.07x slower                                                 |
| json_loads           | 16.1 us                                                | 17.4 us: 1.08x slower                                                 |
| xml_etree_process    | 35.1 ms                                                | 39.5 ms: 1.13x slower                                                 |
| unpickle_list        | 2.65 us                                                | 3.14 us: 1.18x slower                                                 |
| xml_etree_generate   | 48.3 ms                                                | 57.3 ms: 1.19x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.03x slower                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 12.4 ms                                                | 11.7 ms: 1.07x faster                                                 |
| python_startup_no_site | 10.2 ms                                                | 9.54 ms: 1.07x faster                                                 |
| Geometric mean         | (ref)                                                  | 1.07x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 8.53 ms                                                | 7.47 ms: 1.14x faster                                                 |

All benchmarks:
===============

| Benchmark                | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 92.1 us: 3.65x faster                                                 |
| asyncio_tcp              | 651 ms                                                 | 435 ms: 1.50x faster                                                  |
| coverage                 | 58.4 ms                                                | 47.8 ms: 1.22x faster                                                 |
| chaos                    | 49.4 ms                                                | 40.5 ms: 1.22x faster                                                 |
| sqlglot_parse            | 959 us                                                 | 805 us: 1.19x faster                                                  |
| json_dumps               | 7.63 ms                                                | 6.41 ms: 1.19x faster                                                 |
| unpack_sequence          | 34.1 ns                                                | 28.8 ns: 1.19x faster                                                 |
| generators               | 28.8 ms                                                | 24.5 ms: 1.17x faster                                                 |
| raytrace                 | 207 ms                                                 | 177 ms: 1.17x faster                                                  |
| deltablue                | 2.81 ms                                                | 2.43 ms: 1.16x faster                                                 |
| sqlglot_transpile        | 1.12 ms                                                | 981 us: 1.14x faster                                                  |
| async_tree_none          | 286 ms                                                 | 250 ms: 1.14x faster                                                  |
| mako                     | 8.53 ms                                                | 7.47 ms: 1.14x faster                                                 |
| crypto_pyaes             | 51.7 ms                                                | 46.9 ms: 1.10x faster                                                 |
| comprehensions           | 16.1 us                                                | 14.6 us: 1.10x faster                                                 |
| regex_dna                | 152 ms                                                 | 140 ms: 1.08x faster                                                  |
| deepcopy_memo            | 26.3 us                                                | 24.3 us: 1.08x faster                                                 |
| python_startup           | 12.4 ms                                                | 11.7 ms: 1.07x faster                                                 |
| python_startup_no_site   | 10.2 ms                                                | 9.54 ms: 1.07x faster                                                 |
| unpickle                 | 9.67 us                                                | 9.13 us: 1.06x faster                                                 |
| asyncio_tcp_ssl          | 1.44 sec                                               | 1.36 sec: 1.06x faster                                                |
| regex_effbot             | 2.63 ms                                                | 2.50 ms: 1.05x faster                                                 |
| richards_super           | 39.2 ms                                                | 37.4 ms: 1.05x faster                                                 |
| pickle_pure_python       | 201 us                                                 | 193 us: 1.04x faster                                                  |
| scimark_lu               | 73.3 ms                                                | 70.8 ms: 1.04x faster                                                 |
| go                       | 109 ms                                                 | 105 ms: 1.03x faster                                                  |
| async_tree_io            | 704 ms                                                 | 682 ms: 1.03x faster                                                  |
| scimark_sparse_mat_mult  | 3.19 ms                                                | 3.11 ms: 1.03x faster                                                 |
| create_gc_cycles         | 716 us                                                 | 697 us: 1.03x faster                                                  |
| async_tree_memoization   | 336 ms                                                 | 327 ms: 1.03x faster                                                  |
| scimark_monte_carlo      | 46.5 ms                                                | 45.3 ms: 1.03x faster                                                 |
| async_tree_cpu_io_mixed  | 533 ms                                                 | 521 ms: 1.02x faster                                                  |
| nqueens                  | 59.8 ms                                                | 58.6 ms: 1.02x faster                                                 |
| spectral_norm            | 72.6 ms                                                | 71.3 ms: 1.02x faster                                                 |
| pycparser                | 698 ms                                                 | 689 ms: 1.01x faster                                                  |
| unpickle_pure_python     | 159 us                                                 | 158 us: 1.01x faster                                                  |
| gc_traversal             | 2.42 ms                                                | 2.40 ms: 1.01x faster                                                 |
| regex_v8                 | 16.1 ms                                                | 16.2 ms: 1.00x slower                                                 |
| pidigits                 | 281 ms                                                 | 282 ms: 1.00x slower                                                  |
| regex_compile            | 76.7 ms                                                | 77.2 ms: 1.01x slower                                                 |
| coroutines               | 17.8 ms                                                | 17.9 ms: 1.01x slower                                                 |
| dulwich_log              | 30.3 ms                                                | 30.5 ms: 1.01x slower                                                 |
| meteor_contest           | 73.5 ms                                                | 74.1 ms: 1.01x slower                                                 |
| deepcopy                 | 223 us                                                 | 225 us: 1.01x slower                                                  |
| pickle_dict              | 18.0 us                                                | 18.1 us: 1.01x slower                                                 |
| logging_simple           | 3.55 us                                                | 3.59 us: 1.01x slower                                                 |
| docutils                 | 1.47 sec                                               | 1.49 sec: 1.01x slower                                                |
| bench_thread_pool        | 474 us                                                 | 481 us: 1.01x slower                                                  |
| xml_etree_parse          | 108 ms                                                 | 110 ms: 1.01x slower                                                  |
| pickle_list              | 2.81 us                                                | 2.86 us: 1.02x slower                                                 |
| logging_format           | 3.78 us                                                | 3.87 us: 1.02x slower                                                 |
| mdp                      | 1.55 sec                                               | 1.61 sec: 1.04x slower                                                |
| bench_mp_pool            | 43.9 ms                                                | 45.8 ms: 1.04x slower                                                 |
| pickle                   | 7.15 us                                                | 7.46 us: 1.04x slower                                                 |
| float                    | 53.0 ms                                                | 55.4 ms: 1.05x slower                                                 |
| richards                 | 32.2 ms                                                | 33.9 ms: 1.05x slower                                                 |
| deepcopy_reduce          | 1.91 us                                                | 2.01 us: 1.05x slower                                                 |
| tomli_loads              | 1.47 sec                                               | 1.54 sec: 1.05x slower                                                |
| logging_silent           | 68.1 ns                                                | 71.9 ns: 1.06x slower                                                 |
| pprint_pformat           | 954 ms                                                 | 1.01 sec: 1.06x slower                                                |
| pprint_safe_repr         | 466 ms                                                 | 496 ms: 1.06x slower                                                  |
| xml_etree_iterparse      | 70.1 ms                                                | 75.3 ms: 1.07x slower                                                 |
| json                     | 2.78 ms                                                | 2.99 ms: 1.08x slower                                                 |
| json_loads               | 16.1 us                                                | 17.4 us: 1.08x slower                                                 |
| nbody                    | 65.6 ms                                                | 71.2 ms: 1.09x slower                                                 |
| fannkuch                 | 261 ms                                                 | 284 ms: 1.09x slower                                                  |
| sqlglot_normalize        | 171 ms                                                 | 187 ms: 1.10x slower                                                  |
| sqlglot_optimize         | 31.1 ms                                                | 34.2 ms: 1.10x slower                                                 |
| pyflate                  | 310 ms                                                 | 342 ms: 1.10x slower                                                  |
| xml_etree_process        | 35.1 ms                                                | 39.5 ms: 1.13x slower                                                 |
| unpickle_list            | 2.65 us                                                | 3.14 us: 1.18x slower                                                 |
| xml_etree_generate       | 48.3 ms                                                | 57.3 ms: 1.19x slower                                                 |
| pathlib                  | 27.2 ms                                                | 32.5 ms: 1.19x slower                                                 |
| sqlite_synth             | 1.27 us                                                | 1.60 us: 1.26x slower                                                 |
| scimark_sor              | 82.6 ms                                                | 105 ms: 1.28x slower                                                  |
| mypy2                    | 195 ms                                                 | 256 ms: 1.31x slower                                                  |
| telco                    | 3.41 ms                                                | 4.65 ms: 1.37x slower                                                 |
| async_generators         | 196 ms                                                 | 307 ms: 1.56x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.01x faster                                                          |

Benchmark hidden because not significant (3): tornado_http, scimark_fft, hexiom
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
Ignored benchmarks (1) of results/bm-20230905-3.13.0a0-deea7c8/bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8.json: dask


# HPT report

- Reliability score: 66.50% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
