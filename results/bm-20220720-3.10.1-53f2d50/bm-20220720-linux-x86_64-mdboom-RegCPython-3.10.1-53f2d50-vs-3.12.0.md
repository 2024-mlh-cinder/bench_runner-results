
# Results vs. 3.12.0

- fork: mdboom
- ref: RegCPython
- machine: linux-x86_64
- commit hash: 53f2d50
- commit date: 2022-07-20
- overall geometric mean: 1.20x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.13x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220720-linux-x86_64-mdboom-RegCPython-3.10.1-53f2d50 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------:|
| 2to3           | 268 ms                                                 | 313 ms: 1.17x slower                                      |
| docutils       | 2.70 sec                                               | 3.10 sec: 1.15x slower                                    |
| tornado_http   | 99.6 ms                                                | 123 ms: 1.23x slower                                      |
| Geometric mean | (ref)                                                  | 1.18x slower                                              |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220720-linux-x86_64-mdboom-RegCPython-3.10.1-53f2d50 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 188 ms: 1.01x slower                                      |
| nbody          | 88.8 ms                                                | 101 ms: 1.14x slower                                      |
| float          | 80.7 ms                                                | 94.9 ms: 1.18x slower                                     |
| Geometric mean | (ref)                                                  | 1.10x slower                                              |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220720-linux-x86_64-mdboom-RegCPython-3.10.1-53f2d50 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------:|
| regex_effbot   | 3.55 ms                                                | 3.31 ms: 1.07x faster                                     |
| regex_dna      | 209 ms                                                 | 216 ms: 1.03x slower                                      |
| regex_compile  | 144 ms                                                 | 157 ms: 1.09x slower                                      |
| regex_v8       | 22.3 ms                                                | 25.3 ms: 1.13x slower                                     |
| Geometric mean | (ref)                                                  | 1.05x slower                                              |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220720-linux-x86_64-mdboom-RegCPython-3.10.1-53f2d50 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------:|
| pickle_dict          | 31.6 us                                                | 27.2 us: 1.16x faster                                     |
| pickle               | 10.6 us                                                | 10.1 us: 1.05x faster                                     |
| unpickle             | 15.0 us                                                | 14.3 us: 1.05x faster                                     |
| unpickle_list        | 4.95 us                                                | 4.86 us: 1.02x faster                                     |
| pickle_list          | 4.62 us                                                | 4.65 us: 1.01x slower                                     |
| xml_etree_generate   | 84.8 ms                                                | 86.2 ms: 1.02x slower                                     |
| xml_etree_iterparse  | 104 ms                                                 | 106 ms: 1.03x slower                                      |
| xml_etree_parse      | 154 ms                                                 | 158 ms: 1.03x slower                                      |
| json_loads           | 25.2 us                                                | 29.0 us: 1.15x slower                                     |
| xml_etree_process    | 58.6 ms                                                | 68.9 ms: 1.18x slower                                     |
| unpickle_pure_python | 218 us                                                 | 279 us: 1.28x slower                                      |
| json_dumps           | 9.85 ms                                                | 13.4 ms: 1.36x slower                                     |
| pickle_pure_python   | 309 us                                                 | 432 us: 1.40x slower                                      |
| Geometric mean       | (ref)                                                  | 1.08x slower                                              |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220720-linux-x86_64-mdboom-RegCPython-3.10.1-53f2d50 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 5.80 ms: 1.19x faster                                     |
| python_startup         | 9.47 ms                                                | 15.2 ms: 1.60x slower                                     |
| Geometric mean         | (ref)                                                  | 1.16x slower                                              |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220720-linux-x86_64-mdboom-RegCPython-3.10.1-53f2d50 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------:|
| mako      | 10.7 ms                                                | 13.1 ms: 1.22x slower                                     |

All benchmarks:
===============

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220720-linux-x86_64-mdboom-RegCPython-3.10.1-53f2d50 |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------:|
| python_startup_no_site  | 6.90 ms                                                | 5.80 ms: 1.19x faster                                     |
| pickle_dict             | 31.6 us                                                | 27.2 us: 1.16x faster                                     |
| scimark_sparse_mat_mult | 4.74 ms                                                | 4.29 ms: 1.11x faster                                     |
| telco                   | 6.87 ms                                                | 6.27 ms: 1.10x faster                                     |
| regex_effbot            | 3.55 ms                                                | 3.31 ms: 1.07x faster                                     |
| scimark_fft             | 358 ms                                                 | 337 ms: 1.06x faster                                      |
| pickle                  | 10.6 us                                                | 10.1 us: 1.05x faster                                     |
| fannkuch                | 387 ms                                                 | 369 ms: 1.05x faster                                      |
| unpickle                | 15.0 us                                                | 14.3 us: 1.05x faster                                     |
| unpickle_list           | 4.95 us                                                | 4.86 us: 1.02x faster                                     |
| gc_traversal            | 3.84 ms                                                | 3.83 ms: 1.00x faster                                     |
| bench_mp_pool           | 24.0 ms                                                | 24.0 ms: 1.00x faster                                     |
| pickle_list             | 4.62 us                                                | 4.65 us: 1.01x slower                                     |
| pidigits                | 187 ms                                                 | 188 ms: 1.01x slower                                      |
| xml_etree_generate      | 84.8 ms                                                | 86.2 ms: 1.02x slower                                     |
| xml_etree_iterparse     | 104 ms                                                 | 106 ms: 1.03x slower                                      |
| xml_etree_parse         | 154 ms                                                 | 158 ms: 1.03x slower                                      |
| meteor_contest          | 105 ms                                                 | 108 ms: 1.03x slower                                      |
| regex_dna               | 209 ms                                                 | 216 ms: 1.03x slower                                      |
| dulwich_log             | 67.9 ms                                                | 71.2 ms: 1.05x slower                                     |
| sqlite_synth            | 2.76 us                                                | 2.93 us: 1.06x slower                                     |
| mdp                     | 2.57 sec                                               | 2.74 sec: 1.07x slower                                    |
| sqlalchemy_imperative   | 18.4 ms                                                | 19.9 ms: 1.08x slower                                     |
| pathlib                 | 18.5 ms                                                | 20.1 ms: 1.09x slower                                     |
| regex_compile           | 144 ms                                                 | 157 ms: 1.09x slower                                      |
| nqueens                 | 81.1 ms                                                | 88.6 ms: 1.09x slower                                     |
| create_gc_cycles        | 1.52 ms                                                | 1.69 ms: 1.11x slower                                     |
| async_generators        | 440 ms                                                 | 495 ms: 1.12x slower                                      |
| json                    | 4.77 ms                                                | 5.37 ms: 1.13x slower                                     |
| deepcopy_reduce         | 3.14 us                                                | 3.55 us: 1.13x slower                                     |
| regex_v8                | 22.3 ms                                                | 25.3 ms: 1.13x slower                                     |
| deepcopy                | 355 us                                                 | 404 us: 1.14x slower                                      |
| sqlalchemy_declarative  | 144 ms                                                 | 164 ms: 1.14x slower                                      |
| nbody                   | 88.8 ms                                                | 101 ms: 1.14x slower                                      |
| bench_thread_pool       | 827 us                                                 | 947 us: 1.15x slower                                      |
| docutils                | 2.70 sec                                               | 3.10 sec: 1.15x slower                                    |
| json_loads              | 25.2 us                                                | 29.0 us: 1.15x slower                                     |
| spectral_norm           | 106 ms                                                 | 124 ms: 1.17x slower                                      |
| 2to3                    | 268 ms                                                 | 313 ms: 1.17x slower                                      |
| float                   | 80.7 ms                                                | 94.9 ms: 1.18x slower                                     |
| xml_etree_process       | 58.6 ms                                                | 68.9 ms: 1.18x slower                                     |
| unpack_sequence         | 44.8 ns                                                | 52.8 ns: 1.18x slower                                     |
| pycparser               | 1.15 sec                                               | 1.37 sec: 1.19x slower                                    |
| deepcopy_memo           | 37.4 us                                                | 45.1 us: 1.20x slower                                     |
| scimark_monte_carlo     | 71.0 ms                                                | 85.8 ms: 1.21x slower                                     |
| logging_format          | 6.90 us                                                | 8.42 us: 1.22x slower                                     |
| mako                    | 10.7 ms                                                | 13.1 ms: 1.22x slower                                     |
| tornado_http            | 99.6 ms                                                | 123 ms: 1.23x slower                                      |
| pprint_safe_repr        | 735 ms                                                 | 914 ms: 1.24x slower                                      |
| sqlglot_optimize        | 53.3 ms                                                | 66.5 ms: 1.25x slower                                     |
| pprint_pformat          | 1.50 sec                                               | 1.88 sec: 1.25x slower                                    |
| coroutines              | 22.4 ms                                                | 28.6 ms: 1.27x slower                                     |
| unpickle_pure_python    | 218 us                                                 | 279 us: 1.28x slower                                      |
| logging_simple          | 6.18 us                                                | 7.90 us: 1.28x slower                                     |
| pyflate                 | 450 ms                                                 | 580 ms: 1.29x slower                                      |
| sqlglot_normalize       | 107 ms                                                 | 139 ms: 1.30x slower                                      |
| scimark_lu              | 114 ms                                                 | 153 ms: 1.34x slower                                      |
| json_dumps              | 9.85 ms                                                | 13.4 ms: 1.36x slower                                     |
| async_tree_cpu_io_mixed | 714 ms                                                 | 970 ms: 1.36x slower                                      |
| crypto_pyaes            | 77.2 ms                                                | 106 ms: 1.37x slower                                      |
| hexiom                  | 6.12 ms                                                | 8.43 ms: 1.38x slower                                     |
| async_tree_io           | 1.16 sec                                               | 1.61 sec: 1.39x slower                                    |
| pickle_pure_python      | 309 us                                                 | 432 us: 1.40x slower                                      |
| sqlglot_transpile       | 1.64 ms                                                | 2.31 ms: 1.41x slower                                     |
| scimark_sor             | 125 ms                                                 | 176 ms: 1.42x slower                                      |
| chaos                   | 63.5 ms                                                | 91.1 ms: 1.43x slower                                     |
| sqlglot_parse           | 1.32 ms                                                | 1.93 ms: 1.46x slower                                     |
| async_tree_memoization  | 573 ms                                                 | 839 ms: 1.46x slower                                      |
| go                      | 136 ms                                                 | 203 ms: 1.50x slower                                      |
| raytrace                | 294 ms                                                 | 440 ms: 1.50x slower                                      |
| async_tree_none         | 469 ms                                                 | 724 ms: 1.54x slower                                      |
| richards                | 43.2 ms                                                | 67.6 ms: 1.56x slower                                     |
| python_startup          | 9.47 ms                                                | 15.2 ms: 1.60x slower                                     |
| asyncio_tcp             | 526 ms                                                 | 885 ms: 1.68x slower                                      |
| generators              | 31.1 ms                                                | 56.3 ms: 1.81x slower                                     |
| logging_silent          | 99.1 ns                                                | 194 ns: 1.95x slower                                      |
| deltablue               | 3.52 ms                                                | 7.24 ms: 2.06x slower                                     |
| Geometric mean          | (ref)                                                  | 1.20x slower                                              |
Ignored benchmarks (8) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: asyncio_tcp_ssl, comprehensions, coverage, dask, mypy2, richards_super, tomli_loads, typing_runtime_protocols
Ignored benchmarks (16) of results/bm-20220720-3.10.1-53f2d50/bm-20220720-linux-x86_64-mdboom-RegCPython-3.10.1-53f2d50.json: aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, mypy, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.15x
- 95% likely to have a slowdown of 1.14x
- 99% likely to have a slowdown of 1.13x
