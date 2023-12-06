
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: darwin-arm64
- commit hash: 0553fdf
- commit date: 2023-09-10
- overall geometric mean: 1.02x faster
- HPT reliability: 66.15%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230910-darwin-arm64-python-main-3.13.0a0-0553fdf |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| docutils       | 1.47 sec                                               | 1.50 sec: 1.02x slower                                |
| Geometric mean | (ref)                                                  | 1.01x slower                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230910-darwin-arm64-python-main-3.13.0a0-0553fdf |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pidigits       | 281 ms                                                 | 282 ms: 1.01x slower                                  |
| float          | 53.0 ms                                                | 55.2 ms: 1.04x slower                                 |
| nbody          | 65.6 ms                                                | 71.0 ms: 1.08x slower                                 |
| Geometric mean | (ref)                                                  | 1.04x slower                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230910-darwin-arm64-python-main-3.13.0a0-0553fdf |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_dna      | 152 ms                                                 | 140 ms: 1.09x faster                                  |
| regex_effbot   | 2.63 ms                                                | 2.51 ms: 1.05x faster                                 |
| regex_compile  | 76.7 ms                                                | 77.3 ms: 1.01x slower                                 |
| regex_v8       | 16.1 ms                                                | 16.3 ms: 1.01x slower                                 |
| Geometric mean | (ref)                                                  | 1.03x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230910-darwin-arm64-python-main-3.13.0a0-0553fdf |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| json_dumps           | 7.63 ms                                                | 6.48 ms: 1.18x faster                                 |
| unpickle             | 9.67 us                                                | 9.17 us: 1.05x faster                                 |
| pickle_pure_python   | 201 us                                                 | 194 us: 1.03x faster                                  |
| unpickle_pure_python | 159 us                                                 | 157 us: 1.01x faster                                  |
| pickle_list          | 2.81 us                                                | 2.82 us: 1.00x slower                                 |
| pickle_dict          | 18.0 us                                                | 18.1 us: 1.01x slower                                 |
| xml_etree_parse      | 108 ms                                                 | 110 ms: 1.02x slower                                  |
| pickle               | 7.15 us                                                | 7.44 us: 1.04x slower                                 |
| tomli_loads          | 1.47 sec                                               | 1.54 sec: 1.05x slower                                |
| xml_etree_iterparse  | 70.1 ms                                                | 75.4 ms: 1.07x slower                                 |
| json_loads           | 16.1 us                                                | 17.5 us: 1.09x slower                                 |
| xml_etree_process    | 35.1 ms                                                | 39.0 ms: 1.11x slower                                 |
| unpickle_list        | 2.65 us                                                | 3.14 us: 1.18x slower                                 |
| xml_etree_generate   | 48.3 ms                                                | 57.2 ms: 1.19x slower                                 |
| Geometric mean       | (ref)                                                  | 1.03x slower                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230910-darwin-arm64-python-main-3.13.0a0-0553fdf |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup_no_site | 10.2 ms                                                | 9.49 ms: 1.07x faster                                 |
| python_startup         | 12.4 ms                                                | 12.1 ms: 1.03x faster                                 |
| Geometric mean         | (ref)                                                  | 1.05x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230910-darwin-arm64-python-main-3.13.0a0-0553fdf |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 8.53 ms                                                | 7.34 ms: 1.16x faster                                 |

All benchmarks:
===============

| Benchmark                | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230910-darwin-arm64-python-main-3.13.0a0-0553fdf |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 92.4 us: 3.63x faster                                 |
| asyncio_tcp              | 651 ms                                                 | 415 ms: 1.57x faster                                  |
| unpack_sequence          | 34.1 ns                                                | 26.2 ns: 1.30x faster                                 |
| coverage                 | 58.4 ms                                                | 46.8 ms: 1.25x faster                                 |
| chaos                    | 49.4 ms                                                | 40.6 ms: 1.22x faster                                 |
| sqlglot_parse            | 959 us                                                 | 800 us: 1.20x faster                                  |
| json_dumps               | 7.63 ms                                                | 6.48 ms: 1.18x faster                                 |
| generators               | 28.8 ms                                                | 24.5 ms: 1.17x faster                                 |
| raytrace                 | 207 ms                                                 | 177 ms: 1.17x faster                                  |
| mako                     | 8.53 ms                                                | 7.34 ms: 1.16x faster                                 |
| sqlglot_transpile        | 1.12 ms                                                | 975 us: 1.15x faster                                  |
| deltablue                | 2.81 ms                                                | 2.45 ms: 1.15x faster                                 |
| async_tree_none          | 286 ms                                                 | 251 ms: 1.14x faster                                  |
| asyncio_tcp_ssl          | 1.44 sec                                               | 1.27 sec: 1.13x faster                                |
| crypto_pyaes             | 51.7 ms                                                | 46.8 ms: 1.11x faster                                 |
| deepcopy_memo            | 26.3 us                                                | 24.0 us: 1.10x faster                                 |
| comprehensions           | 16.1 us                                                | 14.7 us: 1.10x faster                                 |
| regex_dna                | 152 ms                                                 | 140 ms: 1.09x faster                                  |
| python_startup_no_site   | 10.2 ms                                                | 9.49 ms: 1.07x faster                                 |
| richards_super           | 39.2 ms                                                | 37.2 ms: 1.06x faster                                 |
| unpickle                 | 9.67 us                                                | 9.17 us: 1.05x faster                                 |
| regex_effbot             | 2.63 ms                                                | 2.51 ms: 1.05x faster                                 |
| scimark_lu               | 73.3 ms                                                | 70.6 ms: 1.04x faster                                 |
| scimark_sparse_mat_mult  | 3.19 ms                                                | 3.07 ms: 1.04x faster                                 |
| pickle_pure_python       | 201 us                                                 | 194 us: 1.03x faster                                  |
| go                       | 109 ms                                                 | 105 ms: 1.03x faster                                  |
| scimark_monte_carlo      | 46.5 ms                                                | 45.2 ms: 1.03x faster                                 |
| python_startup           | 12.4 ms                                                | 12.1 ms: 1.03x faster                                 |
| mypy2                    | 195 ms                                                 | 190 ms: 1.03x faster                                  |
| async_tree_cpu_io_mixed  | 533 ms                                                 | 523 ms: 1.02x faster                                  |
| nqueens                  | 59.8 ms                                                | 58.7 ms: 1.02x faster                                 |
| spectral_norm            | 72.6 ms                                                | 71.4 ms: 1.02x faster                                 |
| pycparser                | 698 ms                                                 | 688 ms: 1.01x faster                                  |
| unpickle_pure_python     | 159 us                                                 | 157 us: 1.01x faster                                  |
| async_tree_io            | 704 ms                                                 | 698 ms: 1.01x faster                                  |
| scimark_fft              | 200 ms                                                 | 198 ms: 1.01x faster                                  |
| create_gc_cycles         | 716 us                                                 | 710 us: 1.01x faster                                  |
| gc_traversal             | 2.42 ms                                                | 2.40 ms: 1.00x faster                                 |
| meteor_contest           | 73.5 ms                                                | 73.3 ms: 1.00x faster                                 |
| pickle_list              | 2.81 us                                                | 2.82 us: 1.00x slower                                 |
| deepcopy                 | 223 us                                                 | 224 us: 1.00x slower                                  |
| pidigits                 | 281 ms                                                 | 282 ms: 1.01x slower                                  |
| pickle_dict              | 18.0 us                                                | 18.1 us: 1.01x slower                                 |
| regex_compile            | 76.7 ms                                                | 77.3 ms: 1.01x slower                                 |
| coroutines               | 17.8 ms                                                | 17.9 ms: 1.01x slower                                 |
| bench_thread_pool        | 474 us                                                 | 480 us: 1.01x slower                                  |
| regex_v8                 | 16.1 ms                                                | 16.3 ms: 1.01x slower                                 |
| xml_etree_parse          | 108 ms                                                 | 110 ms: 1.02x slower                                  |
| dulwich_log              | 30.3 ms                                                | 30.8 ms: 1.02x slower                                 |
| logging_simple           | 3.55 us                                                | 3.61 us: 1.02x slower                                 |
| docutils                 | 1.47 sec                                               | 1.50 sec: 1.02x slower                                |
| logging_format           | 3.78 us                                                | 3.90 us: 1.03x slower                                 |
| pickle                   | 7.15 us                                                | 7.44 us: 1.04x slower                                 |
| float                    | 53.0 ms                                                | 55.2 ms: 1.04x slower                                 |
| mdp                      | 1.55 sec                                               | 1.61 sec: 1.04x slower                                |
| richards                 | 32.2 ms                                                | 33.7 ms: 1.05x slower                                 |
| logging_silent           | 68.1 ns                                                | 71.5 ns: 1.05x slower                                 |
| deepcopy_reduce          | 1.91 us                                                | 2.01 us: 1.05x slower                                 |
| tomli_loads              | 1.47 sec                                               | 1.54 sec: 1.05x slower                                |
| bench_mp_pool            | 43.9 ms                                                | 46.6 ms: 1.06x slower                                 |
| pprint_pformat           | 954 ms                                                 | 1.01 sec: 1.06x slower                                |
| pprint_safe_repr         | 466 ms                                                 | 498 ms: 1.07x slower                                  |
| xml_etree_iterparse      | 70.1 ms                                                | 75.4 ms: 1.07x slower                                 |
| nbody                    | 65.6 ms                                                | 71.0 ms: 1.08x slower                                 |
| json_loads               | 16.1 us                                                | 17.5 us: 1.09x slower                                 |
| fannkuch                 | 261 ms                                                 | 285 ms: 1.09x slower                                  |
| sqlglot_normalize        | 171 ms                                                 | 187 ms: 1.09x slower                                  |
| sqlglot_optimize         | 31.1 ms                                                | 34.1 ms: 1.10x slower                                 |
| pyflate                  | 310 ms                                                 | 341 ms: 1.10x slower                                  |
| xml_etree_process        | 35.1 ms                                                | 39.0 ms: 1.11x slower                                 |
| json                     | 2.78 ms                                                | 3.10 ms: 1.12x slower                                 |
| unpickle_list            | 2.65 us                                                | 3.14 us: 1.18x slower                                 |
| xml_etree_generate       | 48.3 ms                                                | 57.2 ms: 1.19x slower                                 |
| pathlib                  | 27.2 ms                                                | 33.0 ms: 1.21x slower                                 |
| sqlite_synth             | 1.27 us                                                | 1.60 us: 1.25x slower                                 |
| scimark_sor              | 82.6 ms                                                | 105 ms: 1.28x slower                                  |
| telco                    | 3.41 ms                                                | 4.54 ms: 1.33x slower                                 |
| async_generators         | 196 ms                                                 | 304 ms: 1.55x slower                                  |
| Geometric mean           | (ref)                                                  | 1.02x faster                                          |

Benchmark hidden because not significant (3): async_tree_memoization, tornado_http, hexiom
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
Ignored benchmarks (1) of results/bm-20230910-3.13.0a0-0553fdf/bm-20230910-darwin-arm64-python-main-3.13.0a0-0553fdf.json: dask


# HPT report

- Reliability score: 66.15% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
