
# Results vs. 3.12.0

- fork: python
- ref: f9774e57d84162ff0cba
- machine: darwin-arm64
- commit hash: f9774e5
- commit date: 2023-03-07
- overall geometric mean: 1.00x slower \*
- HPT reliability: 76.94%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230307-darwin-arm64-python-f9774e57d84162ff0cba-3.12.0a6-f9774e5 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 171 ms                                                 | 165 ms: 1.04x faster                                                  |
| docutils       | 1.54 sec                                               | 1.49 sec: 1.03x faster                                                |
| Geometric mean | (ref)                                                  | 1.03x faster                                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230307-darwin-arm64-python-f9774e57d84162ff0cba-3.12.0a6-f9774e5 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 58.2 ms                                                | 53.5 ms: 1.09x faster                                                 |
| nbody          | 68.6 ms                                                | 66.1 ms: 1.04x faster                                                 |
| pidigits       | 282 ms                                                 | 281 ms: 1.01x faster                                                  |
| Geometric mean | (ref)                                                  | 1.04x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230307-darwin-arm64-python-f9774e57d84162ff0cba-3.12.0a6-f9774e5 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 75.8 ms                                                | 75.4 ms: 1.01x faster                                                 |
| regex_v8       | 16.0 ms                                                | 16.2 ms: 1.01x slower                                                 |
| regex_dna      | 151 ms                                                 | 153 ms: 1.02x slower                                                  |
| regex_effbot   | 2.58 ms                                                | 2.69 ms: 1.04x slower                                                 |
| Geometric mean | (ref)                                                  | 1.02x slower                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230307-darwin-arm64-python-f9774e57d84162ff0cba-3.12.0a6-f9774e5 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| unpickle_list        | 3.22 us                                                | 2.65 us: 1.22x faster                                                 |
| xml_etree_parse      | 109 ms                                                 | 97.9 ms: 1.11x faster                                                 |
| json_loads           | 17.6 us                                                | 16.1 us: 1.09x faster                                                 |
| xml_etree_generate   | 55.8 ms                                                | 51.1 ms: 1.09x faster                                                 |
| xml_etree_iterparse  | 74.3 ms                                                | 71.1 ms: 1.05x faster                                                 |
| xml_etree_process    | 38.5 ms                                                | 37.0 ms: 1.04x faster                                                 |
| json_dumps           | 6.43 ms                                                | 6.18 ms: 1.04x faster                                                 |
| pickle_list          | 2.92 us                                                | 2.83 us: 1.03x faster                                                 |
| pickle_dict          | 18.0 us                                                | 18.0 us: 1.00x faster                                                 |
| unpickle_pure_python | 145 us                                                 | 145 us: 1.01x slower                                                  |
| pickle_pure_python   | 188 us                                                 | 191 us: 1.01x slower                                                  |
| unpickle             | 9.26 us                                                | 9.71 us: 1.05x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.04x faster                                                          |

Benchmark hidden because not significant (1): pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230307-darwin-arm64-python-f9774e57d84162ff0cba-3.12.0a6-f9774e5 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                | 12.5 ms: 1.08x slower                                                 |
| python_startup_no_site | 9.43 ms                                                | 10.4 ms: 1.10x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.09x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230307-darwin-arm64-python-f9774e57d84162ff0cba-3.12.0a6-f9774e5 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 7.57 ms                                                | 7.44 ms: 1.02x faster                                                 |

All benchmarks:
===============

| Benchmark               | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230307-darwin-arm64-python-f9774e57d84162ff0cba-3.12.0a6-f9774e5 |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| unpickle_list           | 3.22 us                                                | 2.65 us: 1.22x faster                                                 |
| sqlite_synth            | 1.58 us                                                | 1.37 us: 1.16x faster                                                 |
| mdp                     | 1.68 sec                                               | 1.50 sec: 1.12x faster                                                |
| async_generators        | 303 ms                                                 | 272 ms: 1.11x faster                                                  |
| xml_etree_parse         | 109 ms                                                 | 97.9 ms: 1.11x faster                                                 |
| telco                   | 3.82 ms                                                | 3.49 ms: 1.09x faster                                                 |
| json                    | 3.05 ms                                                | 2.79 ms: 1.09x faster                                                 |
| json_loads              | 17.6 us                                                | 16.1 us: 1.09x faster                                                 |
| xml_etree_generate      | 55.8 ms                                                | 51.1 ms: 1.09x faster                                                 |
| float                   | 58.2 ms                                                | 53.5 ms: 1.09x faster                                                 |
| raytrace                | 246 ms                                                 | 229 ms: 1.08x faster                                                  |
| scimark_sor             | 94.1 ms                                                | 87.7 ms: 1.07x faster                                                 |
| sqlglot_optimize        | 34.3 ms                                                | 32.1 ms: 1.07x faster                                                 |
| sqlglot_normalize       | 186 ms                                                 | 175 ms: 1.06x faster                                                  |
| pathlib                 | 28.8 ms                                                | 27.5 ms: 1.05x faster                                                 |
| xml_etree_iterparse     | 74.3 ms                                                | 71.1 ms: 1.05x faster                                                 |
| xml_etree_process       | 38.5 ms                                                | 37.0 ms: 1.04x faster                                                 |
| json_dumps              | 6.43 ms                                                | 6.18 ms: 1.04x faster                                                 |
| nbody                   | 68.6 ms                                                | 66.1 ms: 1.04x faster                                                 |
| bench_thread_pool       | 489 us                                                 | 472 us: 1.04x faster                                                  |
| 2to3                    | 171 ms                                                 | 165 ms: 1.04x faster                                                  |
| pprint_pformat          | 1.00 sec                                               | 970 ms: 1.04x faster                                                  |
| pprint_safe_repr        | 493 ms                                                 | 477 ms: 1.03x faster                                                  |
| sqlalchemy_declarative  | 65.9 ms                                                | 63.8 ms: 1.03x faster                                                 |
| fannkuch                | 267 ms                                                 | 258 ms: 1.03x faster                                                  |
| deepcopy_reduce         | 2.02 us                                                | 1.95 us: 1.03x faster                                                 |
| pickle_list             | 2.92 us                                                | 2.83 us: 1.03x faster                                                 |
| docutils                | 1.54 sec                                               | 1.49 sec: 1.03x faster                                                |
| dulwich_log             | 30.3 ms                                                | 29.6 ms: 1.03x faster                                                 |
| generators              | 28.5 ms                                                | 27.9 ms: 1.02x faster                                                 |
| richards                | 31.1 ms                                                | 30.5 ms: 1.02x faster                                                 |
| mako                    | 7.57 ms                                                | 7.44 ms: 1.02x faster                                                 |
| scimark_fft             | 198 ms                                                 | 196 ms: 1.01x faster                                                  |
| logging_simple          | 3.69 us                                                | 3.66 us: 1.01x faster                                                 |
| regex_compile           | 75.8 ms                                                | 75.4 ms: 1.01x faster                                                 |
| deepcopy                | 224 us                                                 | 222 us: 1.01x faster                                                  |
| pidigits                | 282 ms                                                 | 281 ms: 1.01x faster                                                  |
| logging_format          | 3.97 us                                                | 3.95 us: 1.01x faster                                                 |
| coroutines              | 18.2 ms                                                | 18.1 ms: 1.00x faster                                                 |
| pickle_dict             | 18.0 us                                                | 18.0 us: 1.00x faster                                                 |
| deltablue               | 2.59 ms                                                | 2.59 ms: 1.00x faster                                                 |
| spectral_norm           | 75.0 ms                                                | 74.9 ms: 1.00x faster                                                 |
| scimark_sparse_mat_mult | 3.16 ms                                                | 3.17 ms: 1.00x slower                                                 |
| unpickle_pure_python    | 145 us                                                 | 145 us: 1.01x slower                                                  |
| pyflate                 | 329 ms                                                 | 331 ms: 1.01x slower                                                  |
| gc_traversal            | 2.40 ms                                                | 2.43 ms: 1.01x slower                                                 |
| pickle_pure_python      | 188 us                                                 | 191 us: 1.01x slower                                                  |
| regex_v8                | 16.0 ms                                                | 16.2 ms: 1.01x slower                                                 |
| regex_dna               | 151 ms                                                 | 153 ms: 1.02x slower                                                  |
| scimark_monte_carlo     | 50.1 ms                                                | 51.0 ms: 1.02x slower                                                 |
| crypto_pyaes            | 52.3 ms                                                | 53.5 ms: 1.02x slower                                                 |
| logging_silent          | 67.7 ns                                                | 69.3 ns: 1.02x slower                                                 |
| sqlalchemy_imperative   | 7.02 ms                                                | 7.21 ms: 1.03x slower                                                 |
| go                      | 107 ms                                                 | 111 ms: 1.03x slower                                                  |
| scimark_lu              | 71.7 ms                                                | 74.2 ms: 1.04x slower                                                 |
| async_tree_cpu_io_mixed | 526 ms                                                 | 547 ms: 1.04x slower                                                  |
| nqueens                 | 60.6 ms                                                | 63.1 ms: 1.04x slower                                                 |
| regex_effbot            | 2.58 ms                                                | 2.69 ms: 1.04x slower                                                 |
| unpickle                | 9.26 us                                                | 9.71 us: 1.05x slower                                                 |
| hexiom                  | 4.24 ms                                                | 4.46 ms: 1.05x slower                                                 |
| chaos                   | 45.2 ms                                                | 47.8 ms: 1.06x slower                                                 |
| python_startup          | 11.5 ms                                                | 12.5 ms: 1.08x slower                                                 |
| deepcopy_memo           | 24.5 us                                                | 26.4 us: 1.08x slower                                                 |
| async_tree_memoization  | 309 ms                                                 | 336 ms: 1.09x slower                                                  |
| python_startup_no_site  | 9.43 ms                                                | 10.4 ms: 1.10x slower                                                 |
| async_tree_none         | 262 ms                                                 | 289 ms: 1.10x slower                                                  |
| async_tree_io           | 669 ms                                                 | 744 ms: 1.11x slower                                                  |
| comprehensions          | 15.7 us                                                | 17.7 us: 1.13x slower                                                 |
| sqlglot_transpile       | 1.07 ms                                                | 1.22 ms: 1.14x slower                                                 |
| unpack_sequence         | 28.8 ns                                                | 32.9 ns: 1.14x slower                                                 |
| sqlglot_parse           | 898 us                                                 | 1.05 ms: 1.17x slower                                                 |
| coverage                | 51.0 ms                                                | 59.6 ms: 1.17x slower                                                 |
| dask                    | 228 ms                                                 | 325 ms: 1.42x slower                                                  |
| Geometric mean          | (ref)                                                  | 1.00x slower                                                          |

Benchmark hidden because not significant (8): tornado_http, meteor_contest, create_gc_cycles, pickle, pycparser, mypy2, bench_mp_pool, asyncio_tcp
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: asyncio_tcp_ssl, richards_super, tomli_loads, typing_runtime_protocols
Ignored benchmarks (10) of results/bm-20230307-3.12.0a6-f9774e5/bm-20230307-darwin-arm64-python-f9774e57d84162ff0cba-3.12.0a6-f9774e5.json: chameleon, django_template, genshi_text, genshi_xml, html5lib, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 76.94% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
