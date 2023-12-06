
# Results vs. 3.12.0

- fork: python
- ref: v3.10.10
- machine: linux-x86_64
- commit hash: aad5f6a
- commit date: 2023-02-07
- overall geometric mean: 1.25x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.19x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-linux-x86_64-python-v3.10.10-3.10.10-aad5f6a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------:|
| 2to3           | 268 ms                                                 | 335 ms: 1.25x slower                                     |
| docutils       | 2.70 sec                                               | 3.22 sec: 1.19x slower                                   |
| tornado_http   | 99.6 ms                                                | 130 ms: 1.31x slower                                     |
| Geometric mean | (ref)                                                  | 1.25x slower                                             |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-linux-x86_64-python-v3.10.10-3.10.10-aad5f6a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 189 ms: 1.01x slower                                     |
| float          | 80.7 ms                                                | 109 ms: 1.35x slower                                     |
| nbody          | 88.8 ms                                                | 137 ms: 1.54x slower                                     |
| Geometric mean | (ref)                                                  | 1.28x slower                                             |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-linux-x86_64-python-v3.10.10-3.10.10-aad5f6a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------:|
| regex_effbot   | 3.55 ms                                                | 3.62 ms: 1.02x slower                                    |
| regex_dna      | 209 ms                                                 | 216 ms: 1.04x slower                                     |
| regex_v8       | 22.3 ms                                                | 24.1 ms: 1.08x slower                                    |
| regex_compile  | 144 ms                                                 | 177 ms: 1.23x slower                                     |
| Geometric mean | (ref)                                                  | 1.09x slower                                             |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-linux-x86_64-python-v3.10.10-3.10.10-aad5f6a |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------:|
| pickle_list          | 4.62 us                                                | 4.17 us: 1.11x faster                                    |
| pickle               | 10.6 us                                                | 10.2 us: 1.04x faster                                    |
| pickle_dict          | 31.6 us                                                | 30.5 us: 1.04x faster                                    |
| xml_etree_parse      | 154 ms                                                 | 161 ms: 1.05x slower                                     |
| xml_etree_iterparse  | 104 ms                                                 | 110 ms: 1.06x slower                                     |
| xml_etree_generate   | 84.8 ms                                                | 93.0 ms: 1.10x slower                                    |
| json_loads           | 25.2 us                                                | 29.2 us: 1.16x slower                                    |
| xml_etree_process    | 58.6 ms                                                | 74.4 ms: 1.27x slower                                    |
| unpickle_pure_python | 218 us                                                 | 297 us: 1.36x slower                                     |
| json_dumps           | 9.85 ms                                                | 13.6 ms: 1.38x slower                                    |
| pickle_pure_python   | 309 us                                                 | 449 us: 1.45x slower                                     |
| Geometric mean       | (ref)                                                  | 1.11x slower                                             |

Benchmark hidden because not significant (2): unpickle, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-linux-x86_64-python-v3.10.10-3.10.10-aad5f6a |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 5.79 ms: 1.19x faster                                    |
| python_startup         | 9.47 ms                                                | 9.33 ms: 1.02x faster                                    |
| Geometric mean         | (ref)                                                  | 1.10x faster                                             |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-linux-x86_64-python-v3.10.10-3.10.10-aad5f6a |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------:|
| mako      | 10.7 ms                                                | 14.6 ms: 1.36x slower                                    |

All benchmarks:
===============

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-linux-x86_64-python-v3.10.10-3.10.10-aad5f6a |
|-------------------------|:------------------------------------------------------:|:--------------------------------------------------------:|
| coverage                | 94.2 ms                                                | 71.5 ms: 1.32x faster                                    |
| python_startup_no_site  | 6.90 ms                                                | 5.79 ms: 1.19x faster                                    |
| pickle_list             | 4.62 us                                                | 4.17 us: 1.11x faster                                    |
| gc_traversal            | 3.84 ms                                                | 3.54 ms: 1.09x faster                                    |
| pickle                  | 10.6 us                                                | 10.2 us: 1.04x faster                                    |
| pickle_dict             | 31.6 us                                                | 30.5 us: 1.04x faster                                    |
| async_generators        | 440 ms                                                 | 426 ms: 1.03x faster                                     |
| telco                   | 6.87 ms                                                | 6.71 ms: 1.02x faster                                    |
| python_startup          | 9.47 ms                                                | 9.33 ms: 1.02x faster                                    |
| pidigits                | 187 ms                                                 | 189 ms: 1.01x slower                                     |
| regex_effbot            | 3.55 ms                                                | 3.62 ms: 1.02x slower                                    |
| regex_dna               | 209 ms                                                 | 216 ms: 1.04x slower                                     |
| xml_etree_parse         | 154 ms                                                 | 161 ms: 1.05x slower                                     |
| xml_etree_iterparse     | 104 ms                                                 | 110 ms: 1.06x slower                                     |
| pathlib                 | 18.5 ms                                                | 19.7 ms: 1.07x slower                                    |
| create_gc_cycles        | 1.52 ms                                                | 1.63 ms: 1.07x slower                                    |
| sqlite_synth            | 2.76 us                                                | 2.97 us: 1.08x slower                                    |
| meteor_contest          | 105 ms                                                 | 113 ms: 1.08x slower                                     |
| regex_v8                | 22.3 ms                                                | 24.1 ms: 1.08x slower                                    |
| xml_etree_generate      | 84.8 ms                                                | 93.0 ms: 1.10x slower                                    |
| mdp                     | 2.57 sec                                               | 2.82 sec: 1.10x slower                                   |
| dulwich_log             | 67.9 ms                                                | 75.4 ms: 1.11x slower                                    |
| bench_thread_pool       | 827 us                                                 | 919 us: 1.11x slower                                     |
| json                    | 4.77 ms                                                | 5.40 ms: 1.13x slower                                    |
| sqlalchemy_imperative   | 18.4 ms                                                | 20.9 ms: 1.14x slower                                    |
| scimark_sparse_mat_mult | 4.74 ms                                                | 5.39 ms: 1.14x slower                                    |
| scimark_fft             | 358 ms                                                 | 408 ms: 1.14x slower                                     |
| json_loads              | 25.2 us                                                | 29.2 us: 1.16x slower                                    |
| sqlalchemy_declarative  | 144 ms                                                 | 167 ms: 1.16x slower                                     |
| dask                    | 365 ms                                                 | 434 ms: 1.19x slower                                     |
| docutils                | 2.70 sec                                               | 3.22 sec: 1.19x slower                                   |
| deepcopy                | 355 us                                                 | 428 us: 1.20x slower                                     |
| fannkuch                | 387 ms                                                 | 467 ms: 1.21x slower                                     |
| deepcopy_reduce         | 3.14 us                                                | 3.81 us: 1.21x slower                                    |
| sqlglot_optimize        | 53.3 ms                                                | 65.4 ms: 1.23x slower                                    |
| regex_compile           | 144 ms                                                 | 177 ms: 1.23x slower                                     |
| nqueens                 | 81.1 ms                                                | 100 ms: 1.24x slower                                     |
| mypy2                   | 344 ms                                                 | 429 ms: 1.25x slower                                     |
| 2to3                    | 268 ms                                                 | 335 ms: 1.25x slower                                     |
| sqlglot_normalize       | 107 ms                                                 | 136 ms: 1.27x slower                                     |
| xml_etree_process       | 58.6 ms                                                | 74.4 ms: 1.27x slower                                    |
| tornado_http            | 99.6 ms                                                | 130 ms: 1.31x slower                                     |
| pprint_safe_repr        | 735 ms                                                 | 975 ms: 1.33x slower                                     |
| logging_format          | 6.90 us                                                | 9.20 us: 1.33x slower                                    |
| deepcopy_memo           | 37.4 us                                                | 49.9 us: 1.33x slower                                    |
| pycparser               | 1.15 sec                                               | 1.54 sec: 1.34x slower                                   |
| pprint_pformat          | 1.50 sec                                               | 2.02 sec: 1.34x slower                                   |
| spectral_norm           | 106 ms                                                 | 143 ms: 1.35x slower                                     |
| float                   | 80.7 ms                                                | 109 ms: 1.35x slower                                     |
| logging_simple          | 6.18 us                                                | 8.41 us: 1.36x slower                                    |
| unpickle_pure_python    | 218 us                                                 | 297 us: 1.36x slower                                     |
| mako                    | 10.7 ms                                                | 14.6 ms: 1.36x slower                                    |
| coroutines              | 22.4 ms                                                | 30.6 ms: 1.37x slower                                    |
| json_dumps              | 9.85 ms                                                | 13.6 ms: 1.38x slower                                    |
| async_tree_cpu_io_mixed | 714 ms                                                 | 997 ms: 1.40x slower                                     |
| scimark_lu              | 114 ms                                                 | 160 ms: 1.41x slower                                     |
| unpack_sequence         | 44.8 ns                                                | 64.0 ns: 1.43x slower                                    |
| pickle_pure_python      | 309 us                                                 | 449 us: 1.45x slower                                     |
| pyflate                 | 450 ms                                                 | 659 ms: 1.46x slower                                     |
| sqlglot_transpile       | 1.64 ms                                                | 2.41 ms: 1.47x slower                                    |
| scimark_monte_carlo     | 71.0 ms                                                | 105 ms: 1.48x slower                                     |
| crypto_pyaes            | 77.2 ms                                                | 115 ms: 1.49x slower                                     |
| async_tree_memoization  | 573 ms                                                 | 856 ms: 1.49x slower                                     |
| sqlglot_parse           | 1.32 ms                                                | 2.03 ms: 1.53x slower                                    |
| async_tree_none         | 469 ms                                                 | 721 ms: 1.54x slower                                     |
| hexiom                  | 6.12 ms                                                | 9.42 ms: 1.54x slower                                    |
| async_tree_io           | 1.16 sec                                               | 1.78 sec: 1.54x slower                                   |
| nbody                   | 88.8 ms                                                | 137 ms: 1.54x slower                                     |
| scimark_sor             | 125 ms                                                 | 193 ms: 1.55x slower                                     |
| raytrace                | 294 ms                                                 | 463 ms: 1.57x slower                                     |
| go                      | 136 ms                                                 | 226 ms: 1.67x slower                                     |
| chaos                   | 63.5 ms                                                | 106 ms: 1.67x slower                                     |
| richards                | 43.2 ms                                                | 72.6 ms: 1.68x slower                                    |
| asyncio_tcp             | 526 ms                                                 | 915 ms: 1.74x slower                                     |
| logging_silent          | 99.1 ns                                                | 174 ns: 1.76x slower                                     |
| deltablue               | 3.52 ms                                                | 7.41 ms: 2.11x slower                                    |
| generators              | 31.1 ms                                                | 76.1 ms: 2.45x slower                                    |
| Geometric mean          | (ref)                                                  | 1.25x slower                                             |

Benchmark hidden because not significant (3): unpickle, unpickle_list, bench_mp_pool
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: asyncio_tcp_ssl, comprehensions, richards_super, tomli_loads, typing_runtime_protocols
Ignored benchmarks (15) of results/bm-20230207-3.10.10-aad5f6a/bm-20230207-linux-x86_64-python-v3.10.10-3.10.10-aad5f6a.json: aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.22x
- 95% likely to have a slowdown of 1.21x
- 99% likely to have a slowdown of 1.19x
