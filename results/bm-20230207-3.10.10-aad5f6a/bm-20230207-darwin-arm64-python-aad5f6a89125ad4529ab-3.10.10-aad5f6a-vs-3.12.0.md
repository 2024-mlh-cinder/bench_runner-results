
# Results vs. 3.12.0

- fork: python
- ref: aad5f6a89125ad4529ab
- machine: darwin-arm64
- commit hash: aad5f6a
- commit date: 2023-02-07
- overall geometric mean: 1.20x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.16x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-darwin-arm64-python-aad5f6a89125ad4529ab-3.10.10-aad5f6a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| 2to3           | 171 ms                                                 | 203 ms: 1.19x slower                                                 |
| docutils       | 1.54 sec                                               | 1.79 sec: 1.16x slower                                               |
| tornado_http   | 71.0 ms                                                | 92.9 ms: 1.31x slower                                                |
| Geometric mean | (ref)                                                  | 1.22x slower                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-darwin-arm64-python-aad5f6a89125ad4529ab-3.10.10-aad5f6a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| pidigits       | 282 ms                                                 | 282 ms: 1.00x faster                                                 |
| float          | 58.2 ms                                                | 72.3 ms: 1.24x slower                                                |
| nbody          | 68.6 ms                                                | 94.1 ms: 1.37x slower                                                |
| Geometric mean | (ref)                                                  | 1.19x slower                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-darwin-arm64-python-aad5f6a89125ad4529ab-3.10.10-aad5f6a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_effbot   | 2.58 ms                                                | 2.75 ms: 1.07x slower                                                |
| regex_v8       | 16.0 ms                                                | 18.2 ms: 1.14x slower                                                |
| regex_dna      | 151 ms                                                 | 187 ms: 1.24x slower                                                 |
| regex_compile  | 75.8 ms                                                | 96.9 ms: 1.28x slower                                                |
| Geometric mean | (ref)                                                  | 1.18x slower                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-darwin-arm64-python-aad5f6a89125ad4529ab-3.10.10-aad5f6a |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| unpickle_list        | 3.22 us                                                | 2.68 us: 1.20x faster                                                |
| json_loads           | 17.6 us                                                | 16.9 us: 1.04x faster                                                |
| xml_etree_iterparse  | 74.3 ms                                                | 73.1 ms: 1.02x faster                                                |
| xml_etree_parse      | 109 ms                                                 | 107 ms: 1.01x faster                                                 |
| xml_etree_generate   | 55.8 ms                                                | 55.0 ms: 1.01x faster                                                |
| pickle               | 7.45 us                                                | 7.54 us: 1.01x slower                                                |
| pickle_dict          | 18.0 us                                                | 18.7 us: 1.04x slower                                                |
| unpickle             | 9.26 us                                                | 9.86 us: 1.07x slower                                                |
| xml_etree_process    | 38.5 ms                                                | 45.0 ms: 1.17x slower                                                |
| json_dumps           | 6.43 ms                                                | 8.29 ms: 1.29x slower                                                |
| unpickle_pure_python | 145 us                                                 | 204 us: 1.41x slower                                                 |
| pickle_pure_python   | 188 us                                                 | 287 us: 1.53x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.08x slower                                                         |

Benchmark hidden because not significant (1): pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-darwin-arm64-python-aad5f6a89125ad4529ab-3.10.10-aad5f6a |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup_no_site | 9.43 ms                                                | 9.82 ms: 1.04x slower                                                |
| python_startup         | 11.5 ms                                                | 12.7 ms: 1.10x slower                                                |
| Geometric mean         | (ref)                                                  | 1.07x slower                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-darwin-arm64-python-aad5f6a89125ad4529ab-3.10.10-aad5f6a |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 7.57 ms                                                | 10.5 ms: 1.39x slower                                                |

All benchmarks:
===============

| Benchmark               | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-darwin-arm64-python-aad5f6a89125ad4529ab-3.10.10-aad5f6a |
|-------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| async_generators        | 303 ms                                                 | 234 ms: 1.29x faster                                                 |
| coverage                | 51.0 ms                                                | 41.8 ms: 1.22x faster                                                |
| unpickle_list           | 3.22 us                                                | 2.68 us: 1.20x faster                                                |
| bench_mp_pool           | 45.9 ms                                                | 40.9 ms: 1.12x faster                                                |
| sqlite_synth            | 1.58 us                                                | 1.47 us: 1.08x faster                                                |
| telco                   | 3.82 ms                                                | 3.65 ms: 1.04x faster                                                |
| json_loads              | 17.6 us                                                | 16.9 us: 1.04x faster                                                |
| xml_etree_iterparse     | 74.3 ms                                                | 73.1 ms: 1.02x faster                                                |
| xml_etree_parse         | 109 ms                                                 | 107 ms: 1.01x faster                                                 |
| xml_etree_generate      | 55.8 ms                                                | 55.0 ms: 1.01x faster                                                |
| pidigits                | 282 ms                                                 | 282 ms: 1.00x faster                                                 |
| gc_traversal            | 2.40 ms                                                | 2.40 ms: 1.00x faster                                                |
| json                    | 3.05 ms                                                | 3.08 ms: 1.01x slower                                                |
| pickle                  | 7.45 us                                                | 7.54 us: 1.01x slower                                                |
| pickle_dict             | 18.0 us                                                | 18.7 us: 1.04x slower                                                |
| python_startup_no_site  | 9.43 ms                                                | 9.82 ms: 1.04x slower                                                |
| sqlglot_normalize       | 186 ms                                                 | 196 ms: 1.06x slower                                                 |
| meteor_contest          | 72.9 ms                                                | 77.6 ms: 1.06x slower                                                |
| unpickle                | 9.26 us                                                | 9.86 us: 1.07x slower                                                |
| regex_effbot            | 2.58 ms                                                | 2.75 ms: 1.07x slower                                                |
| bench_thread_pool       | 489 us                                                 | 534 us: 1.09x slower                                                 |
| python_startup          | 11.5 ms                                                | 12.7 ms: 1.10x slower                                                |
| scimark_sparse_mat_mult | 3.16 ms                                                | 3.48 ms: 1.10x slower                                                |
| coroutines              | 18.2 ms                                                | 20.2 ms: 1.11x slower                                                |
| sqlglot_optimize        | 34.3 ms                                                | 38.0 ms: 1.11x slower                                                |
| nqueens                 | 60.6 ms                                                | 68.1 ms: 1.12x slower                                                |
| comprehensions          | 15.7 us                                                | 17.7 us: 1.13x slower                                                |
| sqlalchemy_declarative  | 65.9 ms                                                | 74.8 ms: 1.14x slower                                                |
| regex_v8                | 16.0 ms                                                | 18.2 ms: 1.14x slower                                                |
| generators              | 28.5 ms                                                | 32.7 ms: 1.15x slower                                                |
| docutils                | 1.54 sec                                               | 1.79 sec: 1.16x slower                                               |
| dask                    | 228 ms                                                 | 265 ms: 1.16x slower                                                 |
| deepcopy_reduce         | 2.02 us                                                | 2.35 us: 1.17x slower                                                |
| xml_etree_process       | 38.5 ms                                                | 45.0 ms: 1.17x slower                                                |
| scimark_fft             | 198 ms                                                 | 232 ms: 1.17x slower                                                 |
| mypy2                   | 259 ms                                                 | 308 ms: 1.19x slower                                                 |
| fannkuch                | 267 ms                                                 | 317 ms: 1.19x slower                                                 |
| 2to3                    | 171 ms                                                 | 203 ms: 1.19x slower                                                 |
| pprint_safe_repr        | 493 ms                                                 | 600 ms: 1.22x slower                                                 |
| pprint_pformat          | 1.00 sec                                               | 1.23 sec: 1.22x slower                                               |
| dulwich_log             | 30.3 ms                                                | 37.2 ms: 1.23x slower                                                |
| regex_dna               | 151 ms                                                 | 187 ms: 1.24x slower                                                 |
| float                   | 58.2 ms                                                | 72.3 ms: 1.24x slower                                                |
| logging_simple          | 3.69 us                                                | 4.62 us: 1.25x slower                                                |
| create_gc_cycles        | 702 us                                                 | 878 us: 1.25x slower                                                 |
| deepcopy                | 224 us                                                 | 280 us: 1.25x slower                                                 |
| logging_format          | 3.97 us                                                | 5.01 us: 1.26x slower                                                |
| async_tree_cpu_io_mixed | 526 ms                                                 | 667 ms: 1.27x slower                                                 |
| regex_compile           | 75.8 ms                                                | 96.9 ms: 1.28x slower                                                |
| spectral_norm           | 75.0 ms                                                | 96.3 ms: 1.28x slower                                                |
| json_dumps              | 6.43 ms                                                | 8.29 ms: 1.29x slower                                                |
| sqlalchemy_imperative   | 7.02 ms                                                | 9.10 ms: 1.30x slower                                                |
| tornado_http            | 71.0 ms                                                | 92.9 ms: 1.31x slower                                                |
| unpack_sequence         | 28.8 ns                                                | 38.3 ns: 1.33x slower                                                |
| raytrace                | 246 ms                                                 | 330 ms: 1.34x slower                                                 |
| scimark_sor             | 94.1 ms                                                | 126 ms: 1.34x slower                                                 |
| pycparser               | 670 ms                                                 | 913 ms: 1.36x slower                                                 |
| nbody                   | 68.6 ms                                                | 94.1 ms: 1.37x slower                                                |
| pyflate                 | 329 ms                                                 | 455 ms: 1.38x slower                                                 |
| mako                    | 7.57 ms                                                | 10.5 ms: 1.39x slower                                                |
| deepcopy_memo           | 24.5 us                                                | 34.4 us: 1.40x slower                                                |
| unpickle_pure_python    | 145 us                                                 | 204 us: 1.41x slower                                                 |
| sqlglot_transpile       | 1.07 ms                                                | 1.54 ms: 1.43x slower                                                |
| scimark_monte_carlo     | 50.1 ms                                                | 72.8 ms: 1.45x slower                                                |
| asyncio_tcp             | 460 ms                                                 | 673 ms: 1.46x slower                                                 |
| sqlglot_parse           | 898 us                                                 | 1.33 ms: 1.48x slower                                                |
| chaos                   | 45.2 ms                                                | 67.1 ms: 1.48x slower                                                |
| hexiom                  | 4.24 ms                                                | 6.32 ms: 1.49x slower                                                |
| crypto_pyaes            | 52.3 ms                                                | 78.0 ms: 1.49x slower                                                |
| async_tree_io           | 669 ms                                                 | 1.02 sec: 1.52x slower                                               |
| pickle_pure_python      | 188 us                                                 | 287 us: 1.53x slower                                                 |
| async_tree_none         | 262 ms                                                 | 400 ms: 1.53x slower                                                 |
| scimark_lu              | 71.7 ms                                                | 110 ms: 1.53x slower                                                 |
| go                      | 107 ms                                                 | 165 ms: 1.54x slower                                                 |
| async_tree_memoization  | 309 ms                                                 | 488 ms: 1.58x slower                                                 |
| richards                | 31.1 ms                                                | 50.2 ms: 1.62x slower                                                |
| logging_silent          | 67.7 ns                                                | 118 ns: 1.74x slower                                                 |
| deltablue               | 2.59 ms                                                | 5.18 ms: 2.00x slower                                                |
| Geometric mean          | (ref)                                                  | 1.20x slower                                                         |

Benchmark hidden because not significant (3): pathlib, mdp, pickle_list
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: asyncio_tcp_ssl, richards_super, tomli_loads, typing_runtime_protocols
Ignored benchmarks (14) of results/bm-20230207-3.10.10-aad5f6a/bm-20230207-darwin-arm64-python-aad5f6a89125ad4529ab-3.10.10-aad5f6a.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.18x
- 95% likely to have a slowdown of 1.17x
- 99% likely to have a slowdown of 1.16x
