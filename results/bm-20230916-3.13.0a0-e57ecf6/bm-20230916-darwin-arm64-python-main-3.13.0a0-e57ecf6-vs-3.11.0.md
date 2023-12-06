
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: darwin-arm64
- commit hash: e57ecf6
- commit date: 2023-09-16
- overall geometric mean: 1.02x faster
- HPT reliability: 70.83%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230916-darwin-arm64-python-main-3.13.0a0-e57ecf6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| docutils       | 1.47 sec                                               | 1.48 sec: 1.01x slower                                |
| Geometric mean | (ref)                                                  | 1.00x slower                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230916-darwin-arm64-python-main-3.13.0a0-e57ecf6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pidigits       | 281 ms                                                 | 282 ms: 1.00x slower                                  |
| float          | 53.0 ms                                                | 55.4 ms: 1.05x slower                                 |
| nbody          | 65.6 ms                                                | 70.9 ms: 1.08x slower                                 |
| Geometric mean | (ref)                                                  | 1.04x slower                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230916-darwin-arm64-python-main-3.13.0a0-e57ecf6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_dna      | 152 ms                                                 | 140 ms: 1.09x faster                                  |
| regex_effbot   | 2.63 ms                                                | 2.50 ms: 1.05x faster                                 |
| regex_compile  | 76.7 ms                                                | 77.1 ms: 1.01x slower                                 |
| regex_v8       | 16.1 ms                                                | 16.4 ms: 1.02x slower                                 |
| Geometric mean | (ref)                                                  | 1.03x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230916-darwin-arm64-python-main-3.13.0a0-e57ecf6 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| json_dumps           | 7.63 ms                                                | 6.48 ms: 1.18x faster                                 |
| unpickle             | 9.67 us                                                | 9.12 us: 1.06x faster                                 |
| pickle_pure_python   | 201 us                                                 | 194 us: 1.03x faster                                  |
| unpickle_pure_python | 159 us                                                 | 158 us: 1.01x faster                                  |
| pickle_dict          | 18.0 us                                                | 17.8 us: 1.01x faster                                 |
| xml_etree_parse      | 108 ms                                                 | 110 ms: 1.01x slower                                  |
| pickle_list          | 2.81 us                                                | 2.88 us: 1.02x slower                                 |
| pickle               | 7.15 us                                                | 7.39 us: 1.03x slower                                 |
| tomli_loads          | 1.47 sec                                               | 1.54 sec: 1.05x slower                                |
| xml_etree_iterparse  | 70.1 ms                                                | 75.8 ms: 1.08x slower                                 |
| json_loads           | 16.1 us                                                | 17.4 us: 1.08x slower                                 |
| xml_etree_process    | 35.1 ms                                                | 39.1 ms: 1.12x slower                                 |
| xml_etree_generate   | 48.3 ms                                                | 57.1 ms: 1.18x slower                                 |
| unpickle_list        | 2.65 us                                                | 3.22 us: 1.22x slower                                 |
| Geometric mean       | (ref)                                                  | 1.03x slower                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230916-darwin-arm64-python-main-3.13.0a0-e57ecf6 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup_no_site | 10.2 ms                                                | 9.56 ms: 1.06x faster                                 |
| python_startup         | 12.4 ms                                                | 12.2 ms: 1.02x faster                                 |
| Geometric mean         | (ref)                                                  | 1.04x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230916-darwin-arm64-python-main-3.13.0a0-e57ecf6 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 8.53 ms                                                | 7.28 ms: 1.17x faster                                 |

All benchmarks:
===============

| Benchmark                | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230916-darwin-arm64-python-main-3.13.0a0-e57ecf6 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 92.4 us: 3.63x faster                                 |
| asyncio_tcp              | 651 ms                                                 | 404 ms: 1.61x faster                                  |
| unpack_sequence          | 34.1 ns                                                | 26.2 ns: 1.30x faster                                 |
| coverage                 | 58.4 ms                                                | 46.6 ms: 1.25x faster                                 |
| chaos                    | 49.4 ms                                                | 40.6 ms: 1.22x faster                                 |
| sqlglot_parse            | 959 us                                                 | 802 us: 1.20x faster                                  |
| json_dumps               | 7.63 ms                                                | 6.48 ms: 1.18x faster                                 |
| mako                     | 8.53 ms                                                | 7.28 ms: 1.17x faster                                 |
| generators               | 28.8 ms                                                | 24.5 ms: 1.17x faster                                 |
| raytrace                 | 207 ms                                                 | 178 ms: 1.17x faster                                  |
| deltablue                | 2.81 ms                                                | 2.42 ms: 1.16x faster                                 |
| sqlglot_transpile        | 1.12 ms                                                | 977 us: 1.15x faster                                  |
| async_tree_none          | 286 ms                                                 | 250 ms: 1.14x faster                                  |
| asyncio_tcp_ssl          | 1.44 sec                                               | 1.28 sec: 1.13x faster                                |
| crypto_pyaes             | 51.7 ms                                                | 46.8 ms: 1.11x faster                                 |
| comprehensions           | 16.1 us                                                | 14.6 us: 1.10x faster                                 |
| regex_dna                | 152 ms                                                 | 140 ms: 1.09x faster                                  |
| deepcopy_memo            | 26.3 us                                                | 24.4 us: 1.08x faster                                 |
| python_startup_no_site   | 10.2 ms                                                | 9.56 ms: 1.06x faster                                 |
| unpickle                 | 9.67 us                                                | 9.12 us: 1.06x faster                                 |
| regex_effbot             | 2.63 ms                                                | 2.50 ms: 1.05x faster                                 |
| richards_super           | 39.2 ms                                                | 37.5 ms: 1.04x faster                                 |
| go                       | 109 ms                                                 | 105 ms: 1.03x faster                                  |
| pickle_pure_python       | 201 us                                                 | 194 us: 1.03x faster                                  |
| scimark_sparse_mat_mult  | 3.19 ms                                                | 3.10 ms: 1.03x faster                                 |
| async_tree_memoization   | 336 ms                                                 | 326 ms: 1.03x faster                                  |
| scimark_monte_carlo      | 46.5 ms                                                | 45.1 ms: 1.03x faster                                 |
| mypy2                    | 195 ms                                                 | 190 ms: 1.03x faster                                  |
| async_tree_cpu_io_mixed  | 533 ms                                                 | 521 ms: 1.02x faster                                  |
| nqueens                  | 59.8 ms                                                | 58.5 ms: 1.02x faster                                 |
| scimark_lu               | 73.3 ms                                                | 71.9 ms: 1.02x faster                                 |
| create_gc_cycles         | 716 us                                                 | 703 us: 1.02x faster                                  |
| python_startup           | 12.4 ms                                                | 12.2 ms: 1.02x faster                                 |
| pycparser                | 698 ms                                                 | 686 ms: 1.02x faster                                  |
| async_tree_io            | 704 ms                                                 | 695 ms: 1.01x faster                                  |
| spectral_norm            | 72.6 ms                                                | 71.7 ms: 1.01x faster                                 |
| unpickle_pure_python     | 159 us                                                 | 158 us: 1.01x faster                                  |
| scimark_fft              | 200 ms                                                 | 198 ms: 1.01x faster                                  |
| pickle_dict              | 18.0 us                                                | 17.8 us: 1.01x faster                                 |
| hexiom                   | 4.72 ms                                                | 4.68 ms: 1.01x faster                                 |
| gc_traversal             | 2.42 ms                                                | 2.40 ms: 1.00x faster                                 |
| pidigits                 | 281 ms                                                 | 282 ms: 1.00x slower                                  |
| meteor_contest           | 73.5 ms                                                | 73.8 ms: 1.00x slower                                 |
| regex_compile            | 76.7 ms                                                | 77.1 ms: 1.01x slower                                 |
| dulwich_log              | 30.3 ms                                                | 30.5 ms: 1.01x slower                                 |
| docutils                 | 1.47 sec                                               | 1.48 sec: 1.01x slower                                |
| deepcopy                 | 223 us                                                 | 225 us: 1.01x slower                                  |
| coroutines               | 17.8 ms                                                | 18.0 ms: 1.01x slower                                 |
| logging_simple           | 3.55 us                                                | 3.59 us: 1.01x slower                                 |
| bench_thread_pool        | 474 us                                                 | 481 us: 1.01x slower                                  |
| xml_etree_parse          | 108 ms                                                 | 110 ms: 1.01x slower                                  |
| regex_v8                 | 16.1 ms                                                | 16.4 ms: 1.02x slower                                 |
| pickle_list              | 2.81 us                                                | 2.88 us: 1.02x slower                                 |
| logging_format           | 3.78 us                                                | 3.88 us: 1.03x slower                                 |
| pickle                   | 7.15 us                                                | 7.39 us: 1.03x slower                                 |
| logging_silent           | 68.1 ns                                                | 70.6 ns: 1.04x slower                                 |
| mdp                      | 1.55 sec                                               | 1.61 sec: 1.04x slower                                |
| float                    | 53.0 ms                                                | 55.4 ms: 1.05x slower                                 |
| tomli_loads              | 1.47 sec                                               | 1.54 sec: 1.05x slower                                |
| richards                 | 32.2 ms                                                | 33.9 ms: 1.05x slower                                 |
| bench_mp_pool            | 43.9 ms                                                | 46.7 ms: 1.06x slower                                 |
| deepcopy_reduce          | 1.91 us                                                | 2.03 us: 1.06x slower                                 |
| pprint_pformat           | 954 ms                                                 | 1.02 sec: 1.07x slower                                |
| nbody                    | 65.6 ms                                                | 70.9 ms: 1.08x slower                                 |
| xml_etree_iterparse      | 70.1 ms                                                | 75.8 ms: 1.08x slower                                 |
| pprint_safe_repr         | 466 ms                                                 | 504 ms: 1.08x slower                                  |
| sqlglot_normalize        | 171 ms                                                 | 185 ms: 1.08x slower                                  |
| json                     | 2.78 ms                                                | 3.01 ms: 1.08x slower                                 |
| json_loads               | 16.1 us                                                | 17.4 us: 1.08x slower                                 |
| sqlglot_optimize         | 31.1 ms                                                | 34.3 ms: 1.10x slower                                 |
| fannkuch                 | 261 ms                                                 | 289 ms: 1.11x slower                                  |
| pyflate                  | 310 ms                                                 | 345 ms: 1.11x slower                                  |
| xml_etree_process        | 35.1 ms                                                | 39.1 ms: 1.12x slower                                 |
| xml_etree_generate       | 48.3 ms                                                | 57.1 ms: 1.18x slower                                 |
| pathlib                  | 27.2 ms                                                | 32.8 ms: 1.21x slower                                 |
| unpickle_list            | 2.65 us                                                | 3.22 us: 1.22x slower                                 |
| sqlite_synth             | 1.27 us                                                | 1.58 us: 1.25x slower                                 |
| scimark_sor              | 82.6 ms                                                | 106 ms: 1.28x slower                                  |
| telco                    | 3.41 ms                                                | 4.68 ms: 1.37x slower                                 |
| async_generators         | 196 ms                                                 | 304 ms: 1.55x slower                                  |
| Geometric mean           | (ref)                                                  | 1.02x faster                                          |

Benchmark hidden because not significant (1): tornado_http
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
Ignored benchmarks (1) of results/bm-20230916-3.13.0a0-e57ecf6/bm-20230916-darwin-arm64-python-main-3.13.0a0-e57ecf6.json: dask


# HPT report

- Reliability score: 70.83% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
