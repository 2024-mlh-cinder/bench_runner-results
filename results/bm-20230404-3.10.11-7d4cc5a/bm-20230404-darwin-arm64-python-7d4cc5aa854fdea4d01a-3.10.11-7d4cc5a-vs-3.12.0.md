
# Results vs. 3.12.0

- fork: python
- ref: 7d4cc5aa854fdea4d01a
- machine: darwin-arm64
- commit hash: 7d4cc5a
- commit date: 2023-04-04
- overall geometric mean: 1.20x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.15x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-darwin-arm64-python-7d4cc5aa854fdea4d01a-3.10.11-7d4cc5a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| 2to3           | 171 ms                                                 | 203 ms: 1.19x slower                                                 |
| docutils       | 1.54 sec                                               | 1.79 sec: 1.16x slower                                               |
| tornado_http   | 71.0 ms                                                | 91.2 ms: 1.28x slower                                                |
| Geometric mean | (ref)                                                  | 1.21x slower                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-darwin-arm64-python-7d4cc5aa854fdea4d01a-3.10.11-7d4cc5a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| pidigits       | 282 ms                                                 | 282 ms: 1.00x faster                                                 |
| float          | 58.2 ms                                                | 72.2 ms: 1.24x slower                                                |
| nbody          | 68.6 ms                                                | 94.0 ms: 1.37x slower                                                |
| Geometric mean | (ref)                                                  | 1.19x slower                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-darwin-arm64-python-7d4cc5aa854fdea4d01a-3.10.11-7d4cc5a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_effbot   | 2.58 ms                                                | 2.69 ms: 1.04x slower                                                |
| regex_v8       | 16.0 ms                                                | 18.0 ms: 1.13x slower                                                |
| regex_dna      | 151 ms                                                 | 185 ms: 1.22x slower                                                 |
| regex_compile  | 75.8 ms                                                | 96.9 ms: 1.28x slower                                                |
| Geometric mean | (ref)                                                  | 1.16x slower                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-darwin-arm64-python-7d4cc5aa854fdea4d01a-3.10.11-7d4cc5a |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| unpickle_list        | 3.22 us                                                | 2.69 us: 1.20x faster                                                |
| json_loads           | 17.6 us                                                | 16.8 us: 1.04x faster                                                |
| xml_etree_generate   | 55.8 ms                                                | 54.3 ms: 1.03x faster                                                |
| xml_etree_iterparse  | 74.3 ms                                                | 73.2 ms: 1.01x faster                                                |
| pickle_list          | 2.92 us                                                | 2.90 us: 1.01x faster                                                |
| pickle               | 7.45 us                                                | 7.56 us: 1.01x slower                                                |
| pickle_dict          | 18.0 us                                                | 18.8 us: 1.04x slower                                                |
| unpickle             | 9.26 us                                                | 9.89 us: 1.07x slower                                                |
| xml_etree_process    | 38.5 ms                                                | 44.9 ms: 1.16x slower                                                |
| json_dumps           | 6.43 ms                                                | 8.27 ms: 1.29x slower                                                |
| unpickle_pure_python | 145 us                                                 | 204 us: 1.41x slower                                                 |
| pickle_pure_python   | 188 us                                                 | 285 us: 1.51x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.08x slower                                                         |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-darwin-arm64-python-7d4cc5aa854fdea4d01a-3.10.11-7d4cc5a |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup_no_site | 9.43 ms                                                | 9.13 ms: 1.03x faster                                                |
| python_startup         | 11.5 ms                                                | 12.1 ms: 1.05x slower                                                |
| Geometric mean         | (ref)                                                  | 1.01x slower                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-darwin-arm64-python-7d4cc5aa854fdea4d01a-3.10.11-7d4cc5a |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 7.57 ms                                                | 10.6 ms: 1.40x slower                                                |

All benchmarks:
===============

| Benchmark               | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-darwin-arm64-python-7d4cc5aa854fdea4d01a-3.10.11-7d4cc5a |
|-------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| async_generators        | 303 ms                                                 | 233 ms: 1.30x faster                                                 |
| coverage                | 51.0 ms                                                | 41.9 ms: 1.22x faster                                                |
| unpickle_list           | 3.22 us                                                | 2.69 us: 1.20x faster                                                |
| bench_mp_pool           | 45.9 ms                                                | 40.2 ms: 1.14x faster                                                |
| sqlite_synth            | 1.58 us                                                | 1.48 us: 1.07x faster                                                |
| telco                   | 3.82 ms                                                | 3.63 ms: 1.05x faster                                                |
| json_loads              | 17.6 us                                                | 16.8 us: 1.04x faster                                                |
| python_startup_no_site  | 9.43 ms                                                | 9.13 ms: 1.03x faster                                                |
| xml_etree_generate      | 55.8 ms                                                | 54.3 ms: 1.03x faster                                                |
| pathlib                 | 28.8 ms                                                | 28.3 ms: 1.02x faster                                                |
| xml_etree_iterparse     | 74.3 ms                                                | 73.2 ms: 1.01x faster                                                |
| pickle_list             | 2.92 us                                                | 2.90 us: 1.01x faster                                                |
| mdp                     | 1.68 sec                                               | 1.67 sec: 1.01x faster                                               |
| gc_traversal            | 2.40 ms                                                | 2.39 ms: 1.00x faster                                                |
| pidigits                | 282 ms                                                 | 282 ms: 1.00x faster                                                 |
| pickle                  | 7.45 us                                                | 7.56 us: 1.01x slower                                                |
| regex_effbot            | 2.58 ms                                                | 2.69 ms: 1.04x slower                                                |
| pickle_dict             | 18.0 us                                                | 18.8 us: 1.04x slower                                                |
| python_startup          | 11.5 ms                                                | 12.1 ms: 1.05x slower                                                |
| sqlglot_normalize       | 186 ms                                                 | 196 ms: 1.05x slower                                                 |
| unpickle                | 9.26 us                                                | 9.89 us: 1.07x slower                                                |
| meteor_contest          | 72.9 ms                                                | 78.0 ms: 1.07x slower                                                |
| bench_thread_pool       | 489 us                                                 | 532 us: 1.09x slower                                                 |
| scimark_sparse_mat_mult | 3.16 ms                                                | 3.46 ms: 1.10x slower                                                |
| sqlglot_optimize        | 34.3 ms                                                | 38.0 ms: 1.11x slower                                                |
| coroutines              | 18.2 ms                                                | 20.1 ms: 1.11x slower                                                |
| nqueens                 | 60.6 ms                                                | 68.0 ms: 1.12x slower                                                |
| regex_v8                | 16.0 ms                                                | 18.0 ms: 1.13x slower                                                |
| dask                    | 228 ms                                                 | 257 ms: 1.13x slower                                                 |
| sqlalchemy_declarative  | 65.9 ms                                                | 75.0 ms: 1.14x slower                                                |
| comprehensions          | 15.7 us                                                | 17.9 us: 1.14x slower                                                |
| generators              | 28.5 ms                                                | 32.7 ms: 1.15x slower                                                |
| docutils                | 1.54 sec                                               | 1.79 sec: 1.16x slower                                               |
| xml_etree_process       | 38.5 ms                                                | 44.9 ms: 1.16x slower                                                |
| scimark_fft             | 198 ms                                                 | 231 ms: 1.17x slower                                                 |
| deepcopy_reduce         | 2.02 us                                                | 2.38 us: 1.18x slower                                                |
| mypy2                   | 259 ms                                                 | 307 ms: 1.18x slower                                                 |
| 2to3                    | 171 ms                                                 | 203 ms: 1.19x slower                                                 |
| fannkuch                | 267 ms                                                 | 319 ms: 1.19x slower                                                 |
| dulwich_log             | 30.3 ms                                                | 36.9 ms: 1.22x slower                                                |
| pprint_safe_repr        | 493 ms                                                 | 602 ms: 1.22x slower                                                 |
| regex_dna               | 151 ms                                                 | 185 ms: 1.22x slower                                                 |
| pprint_pformat          | 1.00 sec                                               | 1.23 sec: 1.23x slower                                               |
| float                   | 58.2 ms                                                | 72.2 ms: 1.24x slower                                                |
| deepcopy                | 224 us                                                 | 279 us: 1.25x slower                                                 |
| create_gc_cycles        | 702 us                                                 | 874 us: 1.25x slower                                                 |
| logging_simple          | 3.69 us                                                | 4.65 us: 1.26x slower                                                |
| async_tree_cpu_io_mixed | 526 ms                                                 | 668 ms: 1.27x slower                                                 |
| logging_format          | 3.97 us                                                | 5.05 us: 1.27x slower                                                |
| regex_compile           | 75.8 ms                                                | 96.9 ms: 1.28x slower                                                |
| sqlalchemy_imperative   | 7.02 ms                                                | 9.01 ms: 1.28x slower                                                |
| tornado_http            | 71.0 ms                                                | 91.2 ms: 1.28x slower                                                |
| spectral_norm           | 75.0 ms                                                | 96.4 ms: 1.29x slower                                                |
| json_dumps              | 6.43 ms                                                | 8.27 ms: 1.29x slower                                                |
| unpack_sequence         | 28.8 ns                                                | 38.3 ns: 1.33x slower                                                |
| scimark_sor             | 94.1 ms                                                | 126 ms: 1.34x slower                                                 |
| raytrace                | 246 ms                                                 | 331 ms: 1.35x slower                                                 |
| pycparser               | 670 ms                                                 | 910 ms: 1.36x slower                                                 |
| nbody                   | 68.6 ms                                                | 94.0 ms: 1.37x slower                                                |
| pyflate                 | 329 ms                                                 | 455 ms: 1.38x slower                                                 |
| mako                    | 7.57 ms                                                | 10.6 ms: 1.40x slower                                                |
| deepcopy_memo           | 24.5 us                                                | 34.5 us: 1.41x slower                                                |
| unpickle_pure_python    | 145 us                                                 | 204 us: 1.41x slower                                                 |
| sqlglot_transpile       | 1.07 ms                                                | 1.53 ms: 1.43x slower                                                |
| scimark_monte_carlo     | 50.1 ms                                                | 72.3 ms: 1.44x slower                                                |
| asyncio_tcp             | 460 ms                                                 | 669 ms: 1.45x slower                                                 |
| sqlglot_parse           | 898 us                                                 | 1.33 ms: 1.48x slower                                                |
| hexiom                  | 4.24 ms                                                | 6.33 ms: 1.49x slower                                                |
| crypto_pyaes            | 52.3 ms                                                | 78.3 ms: 1.50x slower                                                |
| chaos                   | 45.2 ms                                                | 68.0 ms: 1.50x slower                                                |
| pickle_pure_python      | 188 us                                                 | 285 us: 1.51x slower                                                 |
| async_tree_io           | 669 ms                                                 | 1.02 sec: 1.52x slower                                               |
| async_tree_none         | 262 ms                                                 | 399 ms: 1.52x slower                                                 |
| scimark_lu              | 71.7 ms                                                | 110 ms: 1.53x slower                                                 |
| go                      | 107 ms                                                 | 165 ms: 1.54x slower                                                 |
| async_tree_memoization  | 309 ms                                                 | 490 ms: 1.58x slower                                                 |
| richards                | 31.1 ms                                                | 50.7 ms: 1.63x slower                                                |
| logging_silent          | 67.7 ns                                                | 120 ns: 1.77x slower                                                 |
| deltablue               | 2.59 ms                                                | 5.17 ms: 2.00x slower                                                |
| Geometric mean          | (ref)                                                  | 1.20x slower                                                         |

Benchmark hidden because not significant (2): json, xml_etree_parse
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: asyncio_tcp_ssl, richards_super, tomli_loads, typing_runtime_protocols
Ignored benchmarks (14) of results/bm-20230404-3.10.11-7d4cc5a/bm-20230404-darwin-arm64-python-7d4cc5aa854fdea4d01a-3.10.11-7d4cc5a.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.18x
- 95% likely to have a slowdown of 1.16x
- 99% likely to have a slowdown of 1.15x
