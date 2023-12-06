
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin
- machine: darwin-arm64
- commit hash: 7fb79b8
- commit date: 2023-09-05
- overall geometric mean: 1.01x slower
- HPT reliability: 98.73%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-darwin-arm64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| docutils       | 1.47 sec                                               | 1.52 sec: 1.03x slower                                        |
| Geometric mean | (ref)                                                  | 1.01x slower                                                  |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-darwin-arm64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| pidigits       | 281 ms                                                 | 282 ms: 1.00x slower                                          |
| float          | 53.0 ms                                                | 57.1 ms: 1.08x slower                                         |
| nbody          | 65.6 ms                                                | 78.8 ms: 1.20x slower                                         |
| Geometric mean | (ref)                                                  | 1.09x slower                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-darwin-arm64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_dna      | 152 ms                                                 | 140 ms: 1.08x faster                                          |
| regex_effbot   | 2.63 ms                                                | 2.51 ms: 1.05x faster                                         |
| regex_v8       | 16.1 ms                                                | 16.3 ms: 1.01x slower                                         |
| regex_compile  | 76.7 ms                                                | 81.5 ms: 1.06x slower                                         |
| Geometric mean | (ref)                                                  | 1.01x faster                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-darwin-arm64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| json_dumps           | 7.63 ms                                                | 6.48 ms: 1.18x faster                                         |
| unpickle             | 9.67 us                                                | 9.10 us: 1.06x faster                                         |
| pickle_pure_python   | 201 us                                                 | 195 us: 1.03x faster                                          |
| pickle_dict          | 18.0 us                                                | 17.8 us: 1.01x faster                                         |
| xml_etree_parse      | 108 ms                                                 | 111 ms: 1.02x slower                                          |
| unpickle_pure_python | 159 us                                                 | 164 us: 1.03x slower                                          |
| tomli_loads          | 1.47 sec                                               | 1.52 sec: 1.04x slower                                        |
| pickle               | 7.15 us                                                | 7.45 us: 1.04x slower                                         |
| pickle_list          | 2.81 us                                                | 2.93 us: 1.04x slower                                         |
| json_loads           | 16.1 us                                                | 17.6 us: 1.09x slower                                         |
| xml_etree_iterparse  | 70.1 ms                                                | 77.3 ms: 1.10x slower                                         |
| xml_etree_process    | 35.1 ms                                                | 39.9 ms: 1.14x slower                                         |
| unpickle_list        | 2.65 us                                                | 3.18 us: 1.20x slower                                         |
| xml_etree_generate   | 48.3 ms                                                | 58.0 ms: 1.20x slower                                         |
| Geometric mean       | (ref)                                                  | 1.04x slower                                                  |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-darwin-arm64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 12.4 ms                                                | 11.7 ms: 1.06x faster                                         |
| python_startup_no_site | 10.2 ms                                                | 9.58 ms: 1.06x faster                                         |
| Geometric mean         | (ref)                                                  | 1.06x faster                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-darwin-arm64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 8.53 ms                                                | 7.66 ms: 1.11x faster                                         |

All benchmarks:
===============

| Benchmark                | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-darwin-arm64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 95.7 us: 3.51x faster                                         |
| asyncio_tcp              | 651 ms                                                 | 418 ms: 1.56x faster                                          |
| unpack_sequence          | 34.1 ns                                                | 26.4 ns: 1.29x faster                                         |
| coverage                 | 58.4 ms                                                | 47.5 ms: 1.23x faster                                         |
| json_dumps               | 7.63 ms                                                | 6.48 ms: 1.18x faster                                         |
| sqlglot_parse            | 959 us                                                 | 819 us: 1.17x faster                                          |
| chaos                    | 49.4 ms                                                | 42.3 ms: 1.17x faster                                         |
| raytrace                 | 207 ms                                                 | 180 ms: 1.15x faster                                          |
| generators               | 28.8 ms                                                | 25.1 ms: 1.15x faster                                         |
| async_tree_none          | 286 ms                                                 | 254 ms: 1.13x faster                                          |
| sqlglot_transpile        | 1.12 ms                                                | 997 us: 1.13x faster                                          |
| deltablue                | 2.81 ms                                                | 2.50 ms: 1.13x faster                                         |
| mako                     | 8.53 ms                                                | 7.66 ms: 1.11x faster                                         |
| regex_dna                | 152 ms                                                 | 140 ms: 1.08x faster                                          |
| crypto_pyaes             | 51.7 ms                                                | 48.6 ms: 1.06x faster                                         |
| unpickle                 | 9.67 us                                                | 9.10 us: 1.06x faster                                         |
| python_startup           | 12.4 ms                                                | 11.7 ms: 1.06x faster                                         |
| python_startup_no_site   | 10.2 ms                                                | 9.58 ms: 1.06x faster                                         |
| asyncio_tcp_ssl          | 1.44 sec                                               | 1.37 sec: 1.05x faster                                        |
| regex_effbot             | 2.63 ms                                                | 2.51 ms: 1.05x faster                                         |
| richards_super           | 39.2 ms                                                | 37.7 ms: 1.04x faster                                         |
| deepcopy_memo            | 26.3 us                                                | 25.5 us: 1.03x faster                                         |
| pickle_pure_python       | 201 us                                                 | 195 us: 1.03x faster                                          |
| create_gc_cycles         | 716 us                                                 | 698 us: 1.02x faster                                          |
| async_tree_io            | 704 ms                                                 | 690 ms: 1.02x faster                                          |
| async_tree_cpu_io_mixed  | 533 ms                                                 | 525 ms: 1.02x faster                                          |
| gc_traversal             | 2.42 ms                                                | 2.40 ms: 1.01x faster                                         |
| pickle_dict              | 18.0 us                                                | 17.8 us: 1.01x faster                                         |
| go                       | 109 ms                                                 | 108 ms: 1.01x faster                                          |
| scimark_lu               | 73.3 ms                                                | 73.2 ms: 1.00x faster                                         |
| pidigits                 | 281 ms                                                 | 282 ms: 1.00x slower                                          |
| regex_v8                 | 16.1 ms                                                | 16.3 ms: 1.01x slower                                         |
| coroutines               | 17.8 ms                                                | 18.0 ms: 1.02x slower                                         |
| logging_simple           | 3.55 us                                                | 3.62 us: 1.02x slower                                         |
| dulwich_log              | 30.3 ms                                                | 31.0 ms: 1.02x slower                                         |
| xml_etree_parse          | 108 ms                                                 | 111 ms: 1.02x slower                                          |
| spectral_norm            | 72.6 ms                                                | 74.3 ms: 1.02x slower                                         |
| deepcopy                 | 223 us                                                 | 229 us: 1.03x slower                                          |
| logging_format           | 3.78 us                                                | 3.89 us: 1.03x slower                                         |
| unpickle_pure_python     | 159 us                                                 | 164 us: 1.03x slower                                          |
| docutils                 | 1.47 sec                                               | 1.52 sec: 1.03x slower                                        |
| tomli_loads              | 1.47 sec                                               | 1.52 sec: 1.04x slower                                        |
| comprehensions           | 16.1 us                                                | 16.8 us: 1.04x slower                                         |
| pickle                   | 7.15 us                                                | 7.45 us: 1.04x slower                                         |
| pickle_list              | 2.81 us                                                | 2.93 us: 1.04x slower                                         |
| scimark_fft              | 200 ms                                                 | 209 ms: 1.05x slower                                          |
| scimark_sparse_mat_mult  | 3.19 ms                                                | 3.35 ms: 1.05x slower                                         |
| richards                 | 32.2 ms                                                | 34.2 ms: 1.06x slower                                         |
| regex_compile            | 76.7 ms                                                | 81.5 ms: 1.06x slower                                         |
| logging_silent           | 68.1 ns                                                | 72.4 ns: 1.06x slower                                         |
| deepcopy_reduce          | 1.91 us                                                | 2.03 us: 1.06x slower                                         |
| meteor_contest           | 73.5 ms                                                | 78.5 ms: 1.07x slower                                         |
| mdp                      | 1.55 sec                                               | 1.66 sec: 1.07x slower                                        |
| float                    | 53.0 ms                                                | 57.1 ms: 1.08x slower                                         |
| bench_thread_pool        | 474 us                                                 | 512 us: 1.08x slower                                          |
| nqueens                  | 59.8 ms                                                | 64.7 ms: 1.08x slower                                         |
| bench_mp_pool            | 43.9 ms                                                | 47.6 ms: 1.08x slower                                         |
| pprint_pformat           | 954 ms                                                 | 1.04 sec: 1.09x slower                                        |
| pprint_safe_repr         | 466 ms                                                 | 508 ms: 1.09x slower                                          |
| json                     | 2.78 ms                                                | 3.03 ms: 1.09x slower                                         |
| json_loads               | 16.1 us                                                | 17.6 us: 1.09x slower                                         |
| pyflate                  | 310 ms                                                 | 340 ms: 1.10x slower                                          |
| hexiom                   | 4.72 ms                                                | 5.20 ms: 1.10x slower                                         |
| xml_etree_iterparse      | 70.1 ms                                                | 77.3 ms: 1.10x slower                                         |
| fannkuch                 | 261 ms                                                 | 289 ms: 1.10x slower                                          |
| sqlglot_normalize        | 171 ms                                                 | 193 ms: 1.13x slower                                          |
| sqlglot_optimize         | 31.1 ms                                                | 35.4 ms: 1.14x slower                                         |
| xml_etree_process        | 35.1 ms                                                | 39.9 ms: 1.14x slower                                         |
| unpickle_list            | 2.65 us                                                | 3.18 us: 1.20x slower                                         |
| nbody                    | 65.6 ms                                                | 78.8 ms: 1.20x slower                                         |
| xml_etree_generate       | 48.3 ms                                                | 58.0 ms: 1.20x slower                                         |
| pathlib                  | 27.2 ms                                                | 32.7 ms: 1.20x slower                                         |
| sqlite_synth             | 1.27 us                                                | 1.61 us: 1.26x slower                                         |
| scimark_sor              | 82.6 ms                                                | 107 ms: 1.29x slower                                          |
| telco                    | 3.41 ms                                                | 4.59 ms: 1.35x slower                                         |
| mypy2                    | 195 ms                                                 | 264 ms: 1.35x slower                                          |
| async_generators         | 196 ms                                                 | 312 ms: 1.59x slower                                          |
| Geometric mean           | (ref)                                                  | 1.01x slower                                                  |

Benchmark hidden because not significant (4): async_tree_memoization, tornado_http, pycparser, scimark_monte_carlo
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
Ignored benchmarks (1) of results/bm-20230905-3.13.0a0-7fb79b8/bm-20230905-darwin-arm64-brandtbucher-justin-3.13.0a0-7fb79b8.json: dask


# HPT report

- Reliability score: 98.73% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
