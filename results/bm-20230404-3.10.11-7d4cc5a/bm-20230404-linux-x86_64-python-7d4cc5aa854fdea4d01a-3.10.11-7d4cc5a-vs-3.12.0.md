
# Results vs. 3.12.0

- fork: python
- ref: 7d4cc5aa854fdea4d01a
- machine: linux-x86_64
- commit hash: 7d4cc5a
- commit date: 2023-04-04
- overall geometric mean: 1.26x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.19x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-linux-x86_64-python-7d4cc5aa854fdea4d01a-3.10.11-7d4cc5a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| 2to3           | 268 ms                                                 | 335 ms: 1.25x slower                                                 |
| docutils       | 2.70 sec                                               | 3.21 sec: 1.19x slower                                               |
| tornado_http   | 99.6 ms                                                | 131 ms: 1.31x slower                                                 |
| Geometric mean | (ref)                                                  | 1.25x slower                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-linux-x86_64-python-7d4cc5aa854fdea4d01a-3.10.11-7d4cc5a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 188 ms: 1.01x slower                                                 |
| float          | 80.7 ms                                                | 108 ms: 1.34x slower                                                 |
| nbody          | 88.8 ms                                                | 137 ms: 1.55x slower                                                 |
| Geometric mean | (ref)                                                  | 1.28x slower                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-linux-x86_64-python-7d4cc5aa854fdea4d01a-3.10.11-7d4cc5a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_effbot   | 3.55 ms                                                | 3.63 ms: 1.02x slower                                                |
| regex_dna      | 209 ms                                                 | 213 ms: 1.02x slower                                                 |
| regex_v8       | 22.3 ms                                                | 25.5 ms: 1.14x slower                                                |
| regex_compile  | 144 ms                                                 | 176 ms: 1.22x slower                                                 |
| Geometric mean | (ref)                                                  | 1.10x slower                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-linux-x86_64-python-7d4cc5aa854fdea4d01a-3.10.11-7d4cc5a |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| pickle_list          | 4.62 us                                                | 4.38 us: 1.05x faster                                                |
| unpickle             | 15.0 us                                                | 14.3 us: 1.05x faster                                                |
| unpickle_list        | 4.95 us                                                | 4.80 us: 1.03x faster                                                |
| pickle               | 10.6 us                                                | 10.4 us: 1.02x faster                                                |
| xml_etree_parse      | 154 ms                                                 | 163 ms: 1.06x slower                                                 |
| xml_etree_iterparse  | 104 ms                                                 | 110 ms: 1.06x slower                                                 |
| pickle_dict          | 31.6 us                                                | 33.7 us: 1.07x slower                                                |
| xml_etree_generate   | 84.8 ms                                                | 93.1 ms: 1.10x slower                                                |
| json_loads           | 25.2 us                                                | 29.0 us: 1.15x slower                                                |
| xml_etree_process    | 58.6 ms                                                | 74.1 ms: 1.27x slower                                                |
| unpickle_pure_python | 218 us                                                 | 298 us: 1.36x slower                                                 |
| json_dumps           | 9.85 ms                                                | 13.6 ms: 1.38x slower                                                |
| pickle_pure_python   | 309 us                                                 | 452 us: 1.46x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.12x slower                                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-linux-x86_64-python-7d4cc5aa854fdea4d01a-3.10.11-7d4cc5a |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 5.83 ms: 1.18x faster                                                |
| python_startup         | 9.47 ms                                                | 14.2 ms: 1.50x slower                                                |
| Geometric mean         | (ref)                                                  | 1.13x slower                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-linux-x86_64-python-7d4cc5aa854fdea4d01a-3.10.11-7d4cc5a |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 14.7 ms: 1.37x slower                                                |

All benchmarks:
===============

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-linux-x86_64-python-7d4cc5aa854fdea4d01a-3.10.11-7d4cc5a |
|-------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| coverage                | 94.2 ms                                                | 72.1 ms: 1.31x faster                                                |
| python_startup_no_site  | 6.90 ms                                                | 5.83 ms: 1.18x faster                                                |
| pickle_list             | 4.62 us                                                | 4.38 us: 1.05x faster                                                |
| unpickle                | 15.0 us                                                | 14.3 us: 1.05x faster                                                |
| async_generators        | 440 ms                                                 | 421 ms: 1.05x faster                                                 |
| gc_traversal            | 3.84 ms                                                | 3.71 ms: 1.04x faster                                                |
| unpickle_list           | 4.95 us                                                | 4.80 us: 1.03x faster                                                |
| pickle                  | 10.6 us                                                | 10.4 us: 1.02x faster                                                |
| telco                   | 6.87 ms                                                | 6.78 ms: 1.01x faster                                                |
| pidigits                | 187 ms                                                 | 188 ms: 1.01x slower                                                 |
| regex_effbot            | 3.55 ms                                                | 3.63 ms: 1.02x slower                                                |
| regex_dna               | 209 ms                                                 | 213 ms: 1.02x slower                                                 |
| xml_etree_parse         | 154 ms                                                 | 163 ms: 1.06x slower                                                 |
| xml_etree_iterparse     | 104 ms                                                 | 110 ms: 1.06x slower                                                 |
| pickle_dict             | 31.6 us                                                | 33.7 us: 1.07x slower                                                |
| pathlib                 | 18.5 ms                                                | 19.9 ms: 1.07x slower                                                |
| meteor_contest          | 105 ms                                                 | 113 ms: 1.08x slower                                                 |
| create_gc_cycles        | 1.52 ms                                                | 1.66 ms: 1.09x slower                                                |
| sqlite_synth            | 2.76 us                                                | 3.02 us: 1.10x slower                                                |
| xml_etree_generate      | 84.8 ms                                                | 93.1 ms: 1.10x slower                                                |
| dulwich_log             | 67.9 ms                                                | 75.5 ms: 1.11x slower                                                |
| mdp                     | 2.57 sec                                               | 2.85 sec: 1.11x slower                                               |
| json                    | 4.77 ms                                                | 5.32 ms: 1.11x slower                                                |
| bench_thread_pool       | 827 us                                                 | 925 us: 1.12x slower                                                 |
| sqlalchemy_imperative   | 18.4 ms                                                | 21.0 ms: 1.14x slower                                                |
| regex_v8                | 22.3 ms                                                | 25.5 ms: 1.14x slower                                                |
| json_loads              | 25.2 us                                                | 29.0 us: 1.15x slower                                                |
| dask                    | 365 ms                                                 | 421 ms: 1.15x slower                                                 |
| scimark_sparse_mat_mult | 4.74 ms                                                | 5.50 ms: 1.16x slower                                                |
| scimark_fft             | 358 ms                                                 | 416 ms: 1.16x slower                                                 |
| sqlalchemy_declarative  | 144 ms                                                 | 168 ms: 1.16x slower                                                 |
| docutils                | 2.70 sec                                               | 3.21 sec: 1.19x slower                                               |
| deepcopy_reduce         | 3.14 us                                                | 3.77 us: 1.20x slower                                                |
| deepcopy                | 355 us                                                 | 429 us: 1.21x slower                                                 |
| nqueens                 | 81.1 ms                                                | 97.9 ms: 1.21x slower                                                |
| fannkuch                | 387 ms                                                 | 471 ms: 1.22x slower                                                 |
| regex_compile           | 144 ms                                                 | 176 ms: 1.22x slower                                                 |
| sqlglot_optimize        | 53.3 ms                                                | 65.5 ms: 1.23x slower                                                |
| mypy2                   | 344 ms                                                 | 429 ms: 1.25x slower                                                 |
| 2to3                    | 268 ms                                                 | 335 ms: 1.25x slower                                                 |
| xml_etree_process       | 58.6 ms                                                | 74.1 ms: 1.27x slower                                                |
| sqlglot_normalize       | 107 ms                                                 | 136 ms: 1.27x slower                                                 |
| pprint_safe_repr        | 735 ms                                                 | 953 ms: 1.30x slower                                                 |
| tornado_http            | 99.6 ms                                                | 131 ms: 1.31x slower                                                 |
| pprint_pformat          | 1.50 sec                                               | 1.97 sec: 1.31x slower                                               |
| comprehensions          | 20.4 us                                                | 27.0 us: 1.32x slower                                                |
| pycparser               | 1.15 sec                                               | 1.52 sec: 1.33x slower                                               |
| logging_format          | 6.90 us                                                | 9.16 us: 1.33x slower                                                |
| deepcopy_memo           | 37.4 us                                                | 49.8 us: 1.33x slower                                                |
| float                   | 80.7 ms                                                | 108 ms: 1.34x slower                                                 |
| spectral_norm           | 106 ms                                                 | 142 ms: 1.34x slower                                                 |
| logging_simple          | 6.18 us                                                | 8.40 us: 1.36x slower                                                |
| async_tree_cpu_io_mixed | 714 ms                                                 | 975 ms: 1.36x slower                                                 |
| unpickle_pure_python    | 218 us                                                 | 298 us: 1.36x slower                                                 |
| mako                    | 10.7 ms                                                | 14.7 ms: 1.37x slower                                                |
| coroutines              | 22.4 ms                                                | 31.0 ms: 1.38x slower                                                |
| json_dumps              | 9.85 ms                                                | 13.6 ms: 1.38x slower                                                |
| scimark_lu              | 114 ms                                                 | 159 ms: 1.39x slower                                                 |
| pickle_pure_python      | 309 us                                                 | 452 us: 1.46x slower                                                 |
| pyflate                 | 450 ms                                                 | 660 ms: 1.47x slower                                                 |
| crypto_pyaes            | 77.2 ms                                                | 114 ms: 1.48x slower                                                 |
| sqlglot_transpile       | 1.64 ms                                                | 2.44 ms: 1.49x slower                                                |
| python_startup          | 9.47 ms                                                | 14.2 ms: 1.50x slower                                                |
| unpack_sequence         | 44.8 ns                                                | 67.6 ns: 1.51x slower                                                |
| async_tree_memoization  | 573 ms                                                 | 873 ms: 1.52x slower                                                 |
| scimark_monte_carlo     | 71.0 ms                                                | 109 ms: 1.53x slower                                                 |
| hexiom                  | 6.12 ms                                                | 9.41 ms: 1.54x slower                                                |
| sqlglot_parse           | 1.32 ms                                                | 2.04 ms: 1.55x slower                                                |
| nbody                   | 88.8 ms                                                | 137 ms: 1.55x slower                                                 |
| scimark_sor             | 125 ms                                                 | 194 ms: 1.56x slower                                                 |
| async_tree_none         | 469 ms                                                 | 732 ms: 1.56x slower                                                 |
| async_tree_io           | 1.16 sec                                               | 1.82 sec: 1.57x slower                                               |
| raytrace                | 294 ms                                                 | 462 ms: 1.57x slower                                                 |
| chaos                   | 63.5 ms                                                | 105 ms: 1.65x slower                                                 |
| go                      | 136 ms                                                 | 227 ms: 1.68x slower                                                 |
| richards                | 43.2 ms                                                | 73.1 ms: 1.69x slower                                                |
| asyncio_tcp             | 526 ms                                                 | 894 ms: 1.70x slower                                                 |
| logging_silent          | 99.1 ns                                                | 175 ns: 1.76x slower                                                 |
| deltablue               | 3.52 ms                                                | 7.35 ms: 2.09x slower                                                |
| generators              | 31.1 ms                                                | 75.5 ms: 2.43x slower                                                |
| Geometric mean          | (ref)                                                  | 1.26x slower                                                         |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: asyncio_tcp_ssl, richards_super, tomli_loads, typing_runtime_protocols
Ignored benchmarks (15) of results/bm-20230404-3.10.11-7d4cc5a/bm-20230404-linux-x86_64-python-7d4cc5aa854fdea4d01a-3.10.11-7d4cc5a.json: aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.22x
- 95% likely to have a slowdown of 1.21x
- 99% likely to have a slowdown of 1.19x
