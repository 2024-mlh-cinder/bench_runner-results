
# Results vs. 3.12.0

- fork: python
- ref: 1dd9be6584413fbfa823
- machine: darwin-arm64
- commit hash: 1dd9be6
- commit date: 2022-12-06
- overall geometric mean: 1.19x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.14x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-darwin-arm64-python-1dd9be6584413fbfa823-3.10.9-1dd9be6 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| 2to3           | 171 ms                                                 | 223 ms: 1.31x slower                                                |
| docutils       | 1.54 sec                                               | 1.77 sec: 1.15x slower                                              |
| tornado_http   | 71.0 ms                                                | 93.5 ms: 1.32x slower                                               |
| Geometric mean | (ref)                                                  | 1.26x slower                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-darwin-arm64-python-1dd9be6584413fbfa823-3.10.9-1dd9be6 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| pidigits       | 282 ms                                                 | 284 ms: 1.00x slower                                                |
| float          | 58.2 ms                                                | 72.1 ms: 1.24x slower                                               |
| nbody          | 68.6 ms                                                | 92.6 ms: 1.35x slower                                               |
| Geometric mean | (ref)                                                  | 1.19x slower                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-darwin-arm64-python-1dd9be6584413fbfa823-3.10.9-1dd9be6 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_effbot   | 2.58 ms                                                | 2.64 ms: 1.02x slower                                               |
| regex_v8       | 16.0 ms                                                | 18.3 ms: 1.15x slower                                               |
| regex_dna      | 151 ms                                                 | 180 ms: 1.19x slower                                                |
| regex_compile  | 75.8 ms                                                | 96.5 ms: 1.27x slower                                               |
| Geometric mean | (ref)                                                  | 1.15x slower                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-darwin-arm64-python-1dd9be6584413fbfa823-3.10.9-1dd9be6 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| unpickle_list        | 3.22 us                                                | 2.66 us: 1.21x faster                                               |
| xml_etree_parse      | 109 ms                                                 | 100 ms: 1.08x faster                                                |
| xml_etree_iterparse  | 74.3 ms                                                | 69.0 ms: 1.08x faster                                               |
| json_loads           | 17.6 us                                                | 17.0 us: 1.04x faster                                               |
| xml_etree_generate   | 55.8 ms                                                | 54.3 ms: 1.03x faster                                               |
| pickle_list          | 2.92 us                                                | 2.96 us: 1.01x slower                                               |
| pickle               | 7.45 us                                                | 7.56 us: 1.01x slower                                               |
| pickle_dict          | 18.0 us                                                | 18.8 us: 1.04x slower                                               |
| unpickle             | 9.26 us                                                | 9.87 us: 1.07x slower                                               |
| xml_etree_process    | 38.5 ms                                                | 44.9 ms: 1.17x slower                                               |
| json_dumps           | 6.43 ms                                                | 8.25 ms: 1.28x slower                                               |
| unpickle_pure_python | 145 us                                                 | 203 us: 1.40x slower                                                |
| pickle_pure_python   | 188 us                                                 | 284 us: 1.51x slower                                                |
| Geometric mean       | (ref)                                                  | 1.07x slower                                                        |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-darwin-arm64-python-1dd9be6584413fbfa823-3.10.9-1dd9be6 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup_no_site | 9.43 ms                                                | 6.95 ms: 1.36x faster                                               |
| python_startup         | 11.5 ms                                                | 9.57 ms: 1.21x faster                                               |
| Geometric mean         | (ref)                                                  | 1.28x faster                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-darwin-arm64-python-1dd9be6584413fbfa823-3.10.9-1dd9be6 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 7.57 ms                                                | 10.7 ms: 1.41x slower                                               |

All benchmarks:
===============

| Benchmark               | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-darwin-arm64-python-1dd9be6584413fbfa823-3.10.9-1dd9be6 |
|-------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup_no_site  | 9.43 ms                                                | 6.95 ms: 1.36x faster                                               |
| pathlib                 | 28.8 ms                                                | 22.0 ms: 1.31x faster                                               |
| async_generators        | 303 ms                                                 | 231 ms: 1.31x faster                                                |
| coverage                | 51.0 ms                                                | 40.6 ms: 1.26x faster                                               |
| unpickle_list           | 3.22 us                                                | 2.66 us: 1.21x faster                                               |
| python_startup          | 11.5 ms                                                | 9.57 ms: 1.21x faster                                               |
| bench_mp_pool           | 45.9 ms                                                | 40.8 ms: 1.12x faster                                               |
| xml_etree_parse         | 109 ms                                                 | 100 ms: 1.08x faster                                                |
| xml_etree_iterparse     | 74.3 ms                                                | 69.0 ms: 1.08x faster                                               |
| sqlite_synth            | 1.58 us                                                | 1.49 us: 1.07x faster                                               |
| telco                   | 3.82 ms                                                | 3.64 ms: 1.05x faster                                               |
| json_loads              | 17.6 us                                                | 17.0 us: 1.04x faster                                               |
| xml_etree_generate      | 55.8 ms                                                | 54.3 ms: 1.03x faster                                               |
| mdp                     | 1.68 sec                                               | 1.66 sec: 1.01x faster                                              |
| pidigits                | 282 ms                                                 | 284 ms: 1.00x slower                                                |
| pickle_list             | 2.92 us                                                | 2.96 us: 1.01x slower                                               |
| pickle                  | 7.45 us                                                | 7.56 us: 1.01x slower                                               |
| json                    | 3.05 ms                                                | 3.11 ms: 1.02x slower                                               |
| regex_effbot            | 2.58 ms                                                | 2.64 ms: 1.02x slower                                               |
| pickle_dict             | 18.0 us                                                | 18.8 us: 1.04x slower                                               |
| sqlglot_normalize       | 186 ms                                                 | 196 ms: 1.05x slower                                                |
| bench_thread_pool       | 489 us                                                 | 518 us: 1.06x slower                                                |
| meteor_contest          | 72.9 ms                                                | 77.4 ms: 1.06x slower                                               |
| unpickle                | 9.26 us                                                | 9.87 us: 1.07x slower                                               |
| scimark_sparse_mat_mult | 3.16 ms                                                | 3.46 ms: 1.10x slower                                               |
| sqlglot_optimize        | 34.3 ms                                                | 37.9 ms: 1.10x slower                                               |
| coroutines              | 18.2 ms                                                | 20.1 ms: 1.11x slower                                               |
| nqueens                 | 60.6 ms                                                | 68.1 ms: 1.12x slower                                               |
| sqlalchemy_declarative  | 65.9 ms                                                | 74.5 ms: 1.13x slower                                               |
| generators              | 28.5 ms                                                | 32.4 ms: 1.14x slower                                               |
| regex_v8                | 16.0 ms                                                | 18.3 ms: 1.15x slower                                               |
| docutils                | 1.54 sec                                               | 1.77 sec: 1.15x slower                                              |
| deepcopy_reduce         | 2.02 us                                                | 2.34 us: 1.16x slower                                               |
| scimark_fft             | 198 ms                                                 | 230 ms: 1.16x slower                                                |
| xml_etree_process       | 38.5 ms                                                | 44.9 ms: 1.17x slower                                               |
| fannkuch                | 267 ms                                                 | 318 ms: 1.19x slower                                                |
| regex_dna               | 151 ms                                                 | 180 ms: 1.19x slower                                                |
| dulwich_log             | 30.3 ms                                                | 36.7 ms: 1.21x slower                                               |
| pprint_safe_repr        | 493 ms                                                 | 603 ms: 1.22x slower                                                |
| pprint_pformat          | 1.00 sec                                               | 1.23 sec: 1.22x slower                                              |
| float                   | 58.2 ms                                                | 72.1 ms: 1.24x slower                                               |
| deepcopy                | 224 us                                                 | 280 us: 1.25x slower                                                |
| logging_simple          | 3.69 us                                                | 4.63 us: 1.25x slower                                               |
| async_tree_cpu_io_mixed | 526 ms                                                 | 661 ms: 1.25x slower                                                |
| logging_format          | 3.97 us                                                | 4.99 us: 1.26x slower                                               |
| regex_compile           | 75.8 ms                                                | 96.5 ms: 1.27x slower                                               |
| sqlalchemy_imperative   | 7.02 ms                                                | 8.96 ms: 1.28x slower                                               |
| spectral_norm           | 75.0 ms                                                | 96.2 ms: 1.28x slower                                               |
| json_dumps              | 6.43 ms                                                | 8.25 ms: 1.28x slower                                               |
| unpack_sequence         | 28.8 ns                                                | 37.4 ns: 1.30x slower                                               |
| 2to3                    | 171 ms                                                 | 223 ms: 1.31x slower                                                |
| tornado_http            | 71.0 ms                                                | 93.5 ms: 1.32x slower                                               |
| raytrace                | 246 ms                                                 | 327 ms: 1.33x slower                                                |
| scimark_sor             | 94.1 ms                                                | 126 ms: 1.34x slower                                                |
| nbody                   | 68.6 ms                                                | 92.6 ms: 1.35x slower                                               |
| pycparser               | 670 ms                                                 | 912 ms: 1.36x slower                                                |
| pyflate                 | 329 ms                                                 | 453 ms: 1.38x slower                                                |
| unpickle_pure_python    | 145 us                                                 | 203 us: 1.40x slower                                                |
| deepcopy_memo           | 24.5 us                                                | 34.5 us: 1.41x slower                                               |
| mako                    | 7.57 ms                                                | 10.7 ms: 1.41x slower                                               |
| scimark_monte_carlo     | 50.1 ms                                                | 72.0 ms: 1.44x slower                                               |
| sqlglot_transpile       | 1.07 ms                                                | 1.55 ms: 1.44x slower                                               |
| chaos                   | 45.2 ms                                                | 66.6 ms: 1.47x slower                                               |
| sqlglot_parse           | 898 us                                                 | 1.33 ms: 1.49x slower                                               |
| hexiom                  | 4.24 ms                                                | 6.30 ms: 1.49x slower                                               |
| crypto_pyaes            | 52.3 ms                                                | 77.9 ms: 1.49x slower                                               |
| async_tree_io           | 669 ms                                                 | 1.00 sec: 1.50x slower                                              |
| async_tree_none         | 262 ms                                                 | 394 ms: 1.50x slower                                                |
| pickle_pure_python      | 188 us                                                 | 284 us: 1.51x slower                                                |
| scimark_lu              | 71.7 ms                                                | 110 ms: 1.53x slower                                                |
| go                      | 107 ms                                                 | 165 ms: 1.54x slower                                                |
| async_tree_memoization  | 309 ms                                                 | 481 ms: 1.55x slower                                                |
| richards                | 31.1 ms                                                | 51.0 ms: 1.64x slower                                               |
| logging_silent          | 67.7 ns                                                | 118 ns: 1.75x slower                                                |
| deltablue               | 2.59 ms                                                | 5.15 ms: 1.99x slower                                               |
| Geometric mean          | (ref)                                                  | 1.19x slower                                                        |
Ignored benchmarks (10) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: asyncio_tcp, asyncio_tcp_ssl, comprehensions, create_gc_cycles, dask, gc_traversal, mypy2, richards_super, tomli_loads, typing_runtime_protocols
Ignored benchmarks (15) of results/bm-20221206-3.10.9-1dd9be6/bm-20221206-darwin-arm64-python-1dd9be6584413fbfa823-3.10.9-1dd9be6.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, mypy, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.16x
- 95% likely to have a slowdown of 1.15x
- 99% likely to have a slowdown of 1.14x
