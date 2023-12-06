
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin_elf
- machine: darwin-arm64
- commit hash: 1799b79
- commit date: 2023-10-02
- overall geometric mean: 1.00x faster
- HPT reliability: 96.90%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-darwin-arm64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| docutils       | 1.47 sec                                               | 1.52 sec: 1.04x slower                                            |
| Geometric mean | (ref)                                                  | 1.01x slower                                                      |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-darwin-arm64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| pidigits       | 281 ms                                                 | 283 ms: 1.01x slower                                              |
| float          | 53.0 ms                                                | 57.0 ms: 1.08x slower                                             |
| nbody          | 65.6 ms                                                | 79.6 ms: 1.21x slower                                             |
| Geometric mean | (ref)                                                  | 1.10x slower                                                      |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-darwin-arm64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| regex_dna      | 152 ms                                                 | 140 ms: 1.08x faster                                              |
| regex_effbot   | 2.63 ms                                                | 2.54 ms: 1.03x faster                                             |
| regex_v8       | 16.1 ms                                                | 16.4 ms: 1.02x slower                                             |
| regex_compile  | 76.7 ms                                                | 81.3 ms: 1.06x slower                                             |
| Geometric mean | (ref)                                                  | 1.01x faster                                                      |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-darwin-arm64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| json_dumps           | 7.63 ms                                                | 6.53 ms: 1.17x faster                                             |
| unpickle             | 9.67 us                                                | 9.17 us: 1.06x faster                                             |
| tomli_loads          | 1.47 sec                                               | 1.39 sec: 1.05x faster                                            |
| pickle_pure_python   | 201 us                                                 | 197 us: 1.02x faster                                              |
| unpickle_pure_python | 159 us                                                 | 160 us: 1.01x slower                                              |
| pickle_list          | 2.81 us                                                | 2.85 us: 1.01x slower                                             |
| xml_etree_parse      | 108 ms                                                 | 111 ms: 1.02x slower                                              |
| pickle               | 7.15 us                                                | 7.47 us: 1.05x slower                                             |
| xml_etree_iterparse  | 70.1 ms                                                | 76.5 ms: 1.09x slower                                             |
| json_loads           | 16.1 us                                                | 17.7 us: 1.10x slower                                             |
| xml_etree_process    | 35.1 ms                                                | 39.6 ms: 1.13x slower                                             |
| unpickle_list        | 2.65 us                                                | 3.16 us: 1.19x slower                                             |
| xml_etree_generate   | 48.3 ms                                                | 57.7 ms: 1.20x slower                                             |
| Geometric mean       | (ref)                                                  | 1.03x slower                                                      |

Benchmark hidden because not significant (1): pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-darwin-arm64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| python_startup_no_site | 10.2 ms                                                | 8.62 ms: 1.18x faster                                             |
| python_startup         | 12.4 ms                                                | 11.2 ms: 1.11x faster                                             |
| Geometric mean         | (ref)                                                  | 1.14x faster                                                      |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-darwin-arm64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| mako      | 8.53 ms                                                | 7.56 ms: 1.13x faster                                             |

All benchmarks:
===============

| Benchmark                | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-darwin-arm64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 94.6 us: 3.55x faster                                             |
| asyncio_tcp              | 651 ms                                                 | 421 ms: 1.55x faster                                              |
| unpack_sequence          | 34.1 ns                                                | 27.3 ns: 1.25x faster                                             |
| coverage                 | 58.4 ms                                                | 46.9 ms: 1.25x faster                                             |
| python_startup_no_site   | 10.2 ms                                                | 8.62 ms: 1.18x faster                                             |
| sqlglot_parse            | 959 us                                                 | 813 us: 1.18x faster                                              |
| json_dumps               | 7.63 ms                                                | 6.53 ms: 1.17x faster                                             |
| generators               | 28.8 ms                                                | 25.1 ms: 1.15x faster                                             |
| sqlglot_transpile        | 1.12 ms                                                | 990 us: 1.13x faster                                              |
| mako                     | 8.53 ms                                                | 7.56 ms: 1.13x faster                                             |
| chaos                    | 49.4 ms                                                | 43.9 ms: 1.13x faster                                             |
| async_tree_none          | 286 ms                                                 | 255 ms: 1.12x faster                                              |
| raytrace                 | 207 ms                                                 | 185 ms: 1.12x faster                                              |
| deltablue                | 2.81 ms                                                | 2.53 ms: 1.11x faster                                             |
| python_startup           | 12.4 ms                                                | 11.2 ms: 1.11x faster                                             |
| asyncio_tcp_ssl          | 1.44 sec                                               | 1.30 sec: 1.11x faster                                            |
| richards_super           | 39.2 ms                                                | 35.6 ms: 1.10x faster                                             |
| regex_dna                | 152 ms                                                 | 140 ms: 1.08x faster                                              |
| crypto_pyaes             | 51.7 ms                                                | 48.7 ms: 1.06x faster                                             |
| unpickle                 | 9.67 us                                                | 9.17 us: 1.06x faster                                             |
| tomli_loads              | 1.47 sec                                               | 1.39 sec: 1.05x faster                                            |
| regex_effbot             | 2.63 ms                                                | 2.54 ms: 1.03x faster                                             |
| deepcopy_memo            | 26.3 us                                                | 25.6 us: 1.03x faster                                             |
| pickle_pure_python       | 201 us                                                 | 197 us: 1.02x faster                                              |
| create_gc_cycles         | 716 us                                                 | 708 us: 1.01x faster                                              |
| async_tree_cpu_io_mixed  | 533 ms                                                 | 528 ms: 1.01x faster                                              |
| richards                 | 32.2 ms                                                | 31.9 ms: 1.01x faster                                             |
| go                       | 109 ms                                                 | 108 ms: 1.00x faster                                              |
| gc_traversal             | 2.42 ms                                                | 2.41 ms: 1.00x faster                                             |
| spectral_norm            | 72.6 ms                                                | 73.0 ms: 1.01x slower                                             |
| pidigits                 | 281 ms                                                 | 283 ms: 1.01x slower                                              |
| unpickle_pure_python     | 159 us                                                 | 160 us: 1.01x slower                                              |
| pickle_list              | 2.81 us                                                | 2.85 us: 1.01x slower                                             |
| coroutines               | 17.8 ms                                                | 18.0 ms: 1.01x slower                                             |
| deepcopy                 | 223 us                                                 | 226 us: 1.02x slower                                              |
| scimark_monte_carlo      | 46.5 ms                                                | 47.3 ms: 1.02x slower                                             |
| logging_simple           | 3.55 us                                                | 3.62 us: 1.02x slower                                             |
| regex_v8                 | 16.1 ms                                                | 16.4 ms: 1.02x slower                                             |
| scimark_sparse_mat_mult  | 3.19 ms                                                | 3.26 ms: 1.02x slower                                             |
| xml_etree_parse          | 108 ms                                                 | 111 ms: 1.02x slower                                              |
| dulwich_log              | 30.3 ms                                                | 31.1 ms: 1.02x slower                                             |
| comprehensions           | 16.1 us                                                | 16.5 us: 1.03x slower                                             |
| logging_format           | 3.78 us                                                | 3.91 us: 1.03x slower                                             |
| docutils                 | 1.47 sec                                               | 1.52 sec: 1.04x slower                                            |
| bench_thread_pool        | 474 us                                                 | 494 us: 1.04x slower                                              |
| pickle                   | 7.15 us                                                | 7.47 us: 1.05x slower                                             |
| deepcopy_reduce          | 1.91 us                                                | 2.00 us: 1.05x slower                                             |
| regex_compile            | 76.7 ms                                                | 81.3 ms: 1.06x slower                                             |
| bench_mp_pool            | 43.9 ms                                                | 46.6 ms: 1.06x slower                                             |
| meteor_contest           | 73.5 ms                                                | 78.1 ms: 1.06x slower                                             |
| logging_silent           | 68.1 ns                                                | 72.6 ns: 1.07x slower                                             |
| pathlib                  | 27.2 ms                                                | 29.1 ms: 1.07x slower                                             |
| nqueens                  | 59.8 ms                                                | 64.0 ms: 1.07x slower                                             |
| float                    | 53.0 ms                                                | 57.0 ms: 1.08x slower                                             |
| scimark_fft              | 200 ms                                                 | 215 ms: 1.08x slower                                              |
| json                     | 2.78 ms                                                | 2.99 ms: 1.08x slower                                             |
| pyflate                  | 310 ms                                                 | 337 ms: 1.09x slower                                              |
| mdp                      | 1.55 sec                                               | 1.68 sec: 1.09x slower                                            |
| xml_etree_iterparse      | 70.1 ms                                                | 76.5 ms: 1.09x slower                                             |
| sqlglot_normalize        | 171 ms                                                 | 186 ms: 1.09x slower                                              |
| json_loads               | 16.1 us                                                | 17.7 us: 1.10x slower                                             |
| hexiom                   | 4.72 ms                                                | 5.29 ms: 1.12x slower                                             |
| sqlglot_optimize         | 31.1 ms                                                | 34.8 ms: 1.12x slower                                             |
| fannkuch                 | 261 ms                                                 | 294 ms: 1.12x slower                                              |
| xml_etree_process        | 35.1 ms                                                | 39.6 ms: 1.13x slower                                             |
| unpickle_list            | 2.65 us                                                | 3.16 us: 1.19x slower                                             |
| xml_etree_generate       | 48.3 ms                                                | 57.7 ms: 1.20x slower                                             |
| nbody                    | 65.6 ms                                                | 79.6 ms: 1.21x slower                                             |
| sqlite_synth             | 1.27 us                                                | 1.63 us: 1.28x slower                                             |
| scimark_sor              | 82.6 ms                                                | 106 ms: 1.29x slower                                              |
| mypy2                    | 195 ms                                                 | 260 ms: 1.33x slower                                              |
| telco                    | 3.41 ms                                                | 4.74 ms: 1.39x slower                                             |
| async_generators         | 196 ms                                                 | 311 ms: 1.58x slower                                              |
| Geometric mean           | (ref)                                                  | 1.00x faster                                                      |

Benchmark hidden because not significant (6): tornado_http, async_tree_memoization, pycparser, pickle_dict, scimark_lu, async_tree_io
Ignored benchmarks (19) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pprint_pformat, pprint_safe_repr, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 96.90% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
