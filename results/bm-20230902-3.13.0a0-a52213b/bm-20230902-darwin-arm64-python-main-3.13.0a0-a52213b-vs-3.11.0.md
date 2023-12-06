
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: darwin-arm64
- commit hash: a52213b
- commit date: 2023-09-02
- overall geometric mean: 1.02x faster
- HPT reliability: 62.47%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230902-darwin-arm64-python-main-3.13.0a0-a52213b |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| docutils       | 1.47 sec                                               | 1.50 sec: 1.02x slower                                |
| Geometric mean | (ref)                                                  | 1.00x slower                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230902-darwin-arm64-python-main-3.13.0a0-a52213b |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pidigits       | 281 ms                                                 | 282 ms: 1.01x slower                                  |
| float          | 53.0 ms                                                | 54.9 ms: 1.04x slower                                 |
| nbody          | 65.6 ms                                                | 69.5 ms: 1.06x slower                                 |
| Geometric mean | (ref)                                                  | 1.03x slower                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230902-darwin-arm64-python-main-3.13.0a0-a52213b |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_effbot   | 2.63 ms                                                | 2.55 ms: 1.03x faster                                 |
| regex_dna      | 152 ms                                                 | 149 ms: 1.02x faster                                  |
| regex_v8       | 16.1 ms                                                | 16.8 ms: 1.05x slower                                 |
| Geometric mean | (ref)                                                  | 1.00x faster                                          |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230902-darwin-arm64-python-main-3.13.0a0-a52213b |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| json_dumps           | 7.63 ms                                                | 6.57 ms: 1.16x faster                                 |
| unpickle             | 9.67 us                                                | 9.06 us: 1.07x faster                                 |
| pickle_pure_python   | 201 us                                                 | 192 us: 1.05x faster                                  |
| unpickle_pure_python | 159 us                                                 | 156 us: 1.02x faster                                  |
| pickle_dict          | 18.0 us                                                | 18.1 us: 1.01x slower                                 |
| xml_etree_parse      | 108 ms                                                 | 110 ms: 1.02x slower                                  |
| pickle_list          | 2.81 us                                                | 2.89 us: 1.03x slower                                 |
| pickle               | 7.15 us                                                | 7.44 us: 1.04x slower                                 |
| tomli_loads          | 1.47 sec                                               | 1.54 sec: 1.05x slower                                |
| xml_etree_iterparse  | 70.1 ms                                                | 75.1 ms: 1.07x slower                                 |
| json_loads           | 16.1 us                                                | 17.5 us: 1.09x slower                                 |
| xml_etree_process    | 35.1 ms                                                | 39.2 ms: 1.12x slower                                 |
| unpickle_list        | 2.65 us                                                | 3.13 us: 1.18x slower                                 |
| xml_etree_generate   | 48.3 ms                                                | 57.3 ms: 1.19x slower                                 |
| Geometric mean       | (ref)                                                  | 1.03x slower                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230902-darwin-arm64-python-main-3.13.0a0-a52213b |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup_no_site | 10.2 ms                                                | 9.50 ms: 1.07x faster                                 |
| python_startup         | 12.4 ms                                                | 11.6 ms: 1.07x faster                                 |
| Geometric mean         | (ref)                                                  | 1.07x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230902-darwin-arm64-python-main-3.13.0a0-a52213b |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 8.53 ms                                                | 7.30 ms: 1.17x faster                                 |

All benchmarks:
===============

| Benchmark                | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230902-darwin-arm64-python-main-3.13.0a0-a52213b |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 92.6 us: 3.63x faster                                 |
| asyncio_tcp              | 651 ms                                                 | 410 ms: 1.59x faster                                  |
| unpack_sequence          | 34.1 ns                                                | 26.4 ns: 1.29x faster                                 |
| chaos                    | 49.4 ms                                                | 40.1 ms: 1.23x faster                                 |
| coverage                 | 58.4 ms                                                | 47.6 ms: 1.23x faster                                 |
| sqlglot_parse            | 959 us                                                 | 798 us: 1.20x faster                                  |
| generators               | 28.8 ms                                                | 24.3 ms: 1.18x faster                                 |
| deltablue                | 2.81 ms                                                | 2.38 ms: 1.18x faster                                 |
| raytrace                 | 207 ms                                                 | 176 ms: 1.17x faster                                  |
| mako                     | 8.53 ms                                                | 7.30 ms: 1.17x faster                                 |
| json_dumps               | 7.63 ms                                                | 6.57 ms: 1.16x faster                                 |
| sqlglot_transpile        | 1.12 ms                                                | 971 us: 1.16x faster                                  |
| async_tree_none          | 286 ms                                                 | 251 ms: 1.14x faster                                  |
| deepcopy_memo            | 26.3 us                                                | 23.9 us: 1.10x faster                                 |
| crypto_pyaes             | 51.7 ms                                                | 47.0 ms: 1.10x faster                                 |
| comprehensions           | 16.1 us                                                | 14.7 us: 1.09x faster                                 |
| python_startup_no_site   | 10.2 ms                                                | 9.50 ms: 1.07x faster                                 |
| python_startup           | 12.4 ms                                                | 11.6 ms: 1.07x faster                                 |
| unpickle                 | 9.67 us                                                | 9.06 us: 1.07x faster                                 |
| asyncio_tcp_ssl          | 1.44 sec                                               | 1.36 sec: 1.06x faster                                |
| pickle_pure_python       | 201 us                                                 | 192 us: 1.05x faster                                  |
| go                       | 109 ms                                                 | 104 ms: 1.05x faster                                  |
| scimark_lu               | 73.3 ms                                                | 70.2 ms: 1.04x faster                                 |
| regex_effbot             | 2.63 ms                                                | 2.55 ms: 1.03x faster                                 |
| scimark_monte_carlo      | 46.5 ms                                                | 45.1 ms: 1.03x faster                                 |
| richards_super           | 39.2 ms                                                | 38.2 ms: 1.03x faster                                 |
| async_tree_io            | 704 ms                                                 | 686 ms: 1.03x faster                                  |
| scimark_sparse_mat_mult  | 3.19 ms                                                | 3.11 ms: 1.03x faster                                 |
| async_tree_memoization   | 336 ms                                                 | 328 ms: 1.03x faster                                  |
| spectral_norm            | 72.6 ms                                                | 70.8 ms: 1.02x faster                                 |
| create_gc_cycles         | 716 us                                                 | 700 us: 1.02x faster                                  |
| unpickle_pure_python     | 159 us                                                 | 156 us: 1.02x faster                                  |
| regex_dna                | 152 ms                                                 | 149 ms: 1.02x faster                                  |
| async_tree_cpu_io_mixed  | 533 ms                                                 | 522 ms: 1.02x faster                                  |
| nqueens                  | 59.8 ms                                                | 58.6 ms: 1.02x faster                                 |
| pycparser                | 698 ms                                                 | 689 ms: 1.01x faster                                  |
| scimark_fft              | 200 ms                                                 | 198 ms: 1.01x faster                                  |
| gc_traversal             | 2.42 ms                                                | 2.40 ms: 1.01x faster                                 |
| hexiom                   | 4.72 ms                                                | 4.70 ms: 1.00x faster                                 |
| pidigits                 | 281 ms                                                 | 282 ms: 1.01x slower                                  |
| pickle_dict              | 18.0 us                                                | 18.1 us: 1.01x slower                                 |
| dulwich_log              | 30.3 ms                                                | 30.5 ms: 1.01x slower                                 |
| deepcopy                 | 223 us                                                 | 225 us: 1.01x slower                                  |
| coroutines               | 17.8 ms                                                | 17.9 ms: 1.01x slower                                 |
| bench_thread_pool        | 474 us                                                 | 479 us: 1.01x slower                                  |
| logging_silent           | 68.1 ns                                                | 68.8 ns: 1.01x slower                                 |
| meteor_contest           | 73.5 ms                                                | 74.7 ms: 1.02x slower                                 |
| xml_etree_parse          | 108 ms                                                 | 110 ms: 1.02x slower                                  |
| docutils                 | 1.47 sec                                               | 1.50 sec: 1.02x slower                                |
| logging_simple           | 3.55 us                                                | 3.64 us: 1.03x slower                                 |
| pickle_list              | 2.81 us                                                | 2.89 us: 1.03x slower                                 |
| float                    | 53.0 ms                                                | 54.9 ms: 1.04x slower                                 |
| logging_format           | 3.78 us                                                | 3.93 us: 1.04x slower                                 |
| pickle                   | 7.15 us                                                | 7.44 us: 1.04x slower                                 |
| bench_mp_pool            | 43.9 ms                                                | 45.8 ms: 1.04x slower                                 |
| mdp                      | 1.55 sec                                               | 1.61 sec: 1.04x slower                                |
| regex_v8                 | 16.1 ms                                                | 16.8 ms: 1.05x slower                                 |
| deepcopy_reduce          | 1.91 us                                                | 2.00 us: 1.05x slower                                 |
| tomli_loads              | 1.47 sec                                               | 1.54 sec: 1.05x slower                                |
| pprint_pformat           | 954 ms                                                 | 1.01 sec: 1.06x slower                                |
| nbody                    | 65.6 ms                                                | 69.5 ms: 1.06x slower                                 |
| pprint_safe_repr         | 466 ms                                                 | 497 ms: 1.07x slower                                  |
| xml_etree_iterparse      | 70.1 ms                                                | 75.1 ms: 1.07x slower                                 |
| richards                 | 32.2 ms                                                | 34.7 ms: 1.08x slower                                 |
| fannkuch                 | 261 ms                                                 | 281 ms: 1.08x slower                                  |
| json                     | 2.78 ms                                                | 2.99 ms: 1.08x slower                                 |
| json_loads               | 16.1 us                                                | 17.5 us: 1.09x slower                                 |
| sqlglot_normalize        | 171 ms                                                 | 187 ms: 1.10x slower                                  |
| pyflate                  | 310 ms                                                 | 342 ms: 1.10x slower                                  |
| sqlglot_optimize         | 31.1 ms                                                | 34.4 ms: 1.11x slower                                 |
| xml_etree_process        | 35.1 ms                                                | 39.2 ms: 1.12x slower                                 |
| unpickle_list            | 2.65 us                                                | 3.13 us: 1.18x slower                                 |
| pathlib                  | 27.2 ms                                                | 32.2 ms: 1.18x slower                                 |
| xml_etree_generate       | 48.3 ms                                                | 57.3 ms: 1.19x slower                                 |
| sqlite_synth             | 1.27 us                                                | 1.59 us: 1.25x slower                                 |
| scimark_sor              | 82.6 ms                                                | 103 ms: 1.25x slower                                  |
| mypy2                    | 195 ms                                                 | 256 ms: 1.31x slower                                  |
| telco                    | 3.41 ms                                                | 4.69 ms: 1.38x slower                                 |
| async_generators         | 196 ms                                                 | 304 ms: 1.55x slower                                  |
| Geometric mean           | (ref)                                                  | 1.02x faster                                          |

Benchmark hidden because not significant (2): tornado_http, regex_compile
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
Ignored benchmarks (1) of results/bm-20230902-3.13.0a0-a52213b/bm-20230902-darwin-arm64-python-main-3.13.0a0-a52213b.json: dask


# HPT report

- Reliability score: 62.47% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
