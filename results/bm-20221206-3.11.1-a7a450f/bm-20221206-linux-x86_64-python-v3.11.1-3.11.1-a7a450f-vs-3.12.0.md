
# Results vs. 3.12.0

- fork: python
- ref: v3.11.1
- machine: linux-x86_64
- commit hash: a7a450f
- commit date: 2022-12-06
- overall geometric mean: 1.03x faster \*
- HPT reliability: 99.99%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-linux-x86_64-python-v3.11.1-3.11.1-a7a450f |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 258 ms: 1.06x faster                                   |
| chameleon      | 7.41 ms                                                | 6.63 ms: 1.12x faster                                  |
| docutils       | 2.75 sec                                               | 2.57 sec: 1.07x faster                                 |
| tornado_http   | 101 ms                                                 | 99.8 ms: 1.01x faster                                  |
| Geometric mean | (ref)                                                  | 1.06x faster                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-linux-x86_64-python-v3.11.1-3.11.1-a7a450f |
|-------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_tree_cpu_io_mixed | 724 ms                                                 | 742 ms: 1.02x slower                                   |
| async_tree_memoization  | 580 ms                                                 | 627 ms: 1.08x slower                                   |
| async_tree_none         | 475 ms                                                 | 523 ms: 1.10x slower                                   |
| async_tree_io           | 1.16 sec                                               | 1.31 sec: 1.12x slower                                 |
| Geometric mean          | (ref)                                                  | 1.08x slower                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-linux-x86_64-python-v3.11.1-3.11.1-a7a450f |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| float          | 83.3 ms                                                | 76.0 ms: 1.10x faster                                  |
| pidigits       | 187 ms                                                 | 190 ms: 1.01x slower                                   |
| nbody          | 92.2 ms                                                | 95.4 ms: 1.03x slower                                  |
| Geometric mean | (ref)                                                  | 1.02x faster                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-linux-x86_64-python-v3.11.1-3.11.1-a7a450f |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 137 ms: 1.08x faster                                   |
| regex_effbot   | 3.57 ms                                                | 3.31 ms: 1.08x faster                                  |
| regex_dna      | 209 ms                                                 | 200 ms: 1.04x faster                                   |
| regex_v8       | 22.7 ms                                                | 22.3 ms: 1.02x faster                                  |
| Geometric mean | (ref)                                                  | 1.05x faster                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-linux-x86_64-python-v3.11.1-3.11.1-a7a450f |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| json_loads           | 28.4 us                                                | 24.0 us: 1.18x faster                                  |
| unpickle             | 15.8 us                                                | 13.4 us: 1.18x faster                                  |
| xml_etree_generate   | 88.7 ms                                                | 76.6 ms: 1.16x faster                                  |
| pickle               | 11.2 us                                                | 9.72 us: 1.15x faster                                  |
| xml_etree_process    | 61.2 ms                                                | 53.7 ms: 1.14x faster                                  |
| pickle_list          | 4.67 us                                                | 4.17 us: 1.12x faster                                  |
| pickle_dict          | 33.5 us                                                | 31.1 us: 1.08x faster                                  |
| pickle_pure_python   | 326 us                                                 | 310 us: 1.05x faster                                   |
| xml_etree_iterparse  | 106 ms                                                 | 103 ms: 1.02x faster                                   |
| unpickle_list        | 5.04 us                                                | 4.95 us: 1.02x faster                                  |
| xml_etree_parse      | 159 ms                                                 | 158 ms: 1.01x faster                                   |
| unpickle_pure_python | 230 us                                                 | 229 us: 1.00x faster                                   |
| json_dumps           | 10.6 ms                                                | 12.6 ms: 1.19x slower                                  |
| Geometric mean       | (ref)                                                  | 1.07x faster                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-linux-x86_64-python-v3.11.1-3.11.1-a7a450f |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup_no_site | 6.92 ms                                                | 5.98 ms: 1.16x faster                                  |
| python_startup         | 9.53 ms                                                | 8.49 ms: 1.12x faster                                  |
| Geometric mean         | (ref)                                                  | 1.14x faster                                           |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-linux-x86_64-python-v3.11.1-3.11.1-a7a450f |
|-----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako            | 11.5 ms                                                | 9.92 ms: 1.16x faster                                  |
| django_template | 35.0 ms                                                | 33.2 ms: 1.05x faster                                  |
| Geometric mean  | (ref)                                                  | 1.11x faster                                           |

All benchmarks:
===============

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-linux-x86_64-python-v3.11.1-3.11.1-a7a450f |
|-------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_generators        | 459 ms                                                 | 358 ms: 1.28x faster                                   |
| unpack_sequence         | 54.2 ns                                                | 44.6 ns: 1.21x faster                                  |
| json_loads              | 28.4 us                                                | 24.0 us: 1.18x faster                                  |
| unpickle                | 15.8 us                                                | 13.4 us: 1.18x faster                                  |
| scimark_sparse_mat_mult | 5.33 ms                                                | 4.59 ms: 1.16x faster                                  |
| scimark_fft             | 381 ms                                                 | 327 ms: 1.16x faster                                   |
| mako                    | 11.5 ms                                                | 9.92 ms: 1.16x faster                                  |
| xml_etree_generate      | 88.7 ms                                                | 76.6 ms: 1.16x faster                                  |
| python_startup_no_site  | 6.92 ms                                                | 5.98 ms: 1.16x faster                                  |
| pickle                  | 11.2 us                                                | 9.72 us: 1.15x faster                                  |
| crypto_pyaes            | 83.6 ms                                                | 72.6 ms: 1.15x faster                                  |
| sqlite_synth            | 2.83 us                                                | 2.47 us: 1.15x faster                                  |
| xml_etree_process       | 61.2 ms                                                | 53.7 ms: 1.14x faster                                  |
| pyflate                 | 471 ms                                                 | 415 ms: 1.13x faster                                   |
| spectral_norm           | 115 ms                                                 | 101 ms: 1.13x faster                                   |
| json                    | 5.22 ms                                                | 4.63 ms: 1.13x faster                                  |
| python_startup          | 9.53 ms                                                | 8.49 ms: 1.12x faster                                  |
| scimark_lu              | 120 ms                                                 | 107 ms: 1.12x faster                                   |
| pickle_list             | 4.67 us                                                | 4.17 us: 1.12x faster                                  |
| chameleon               | 7.41 ms                                                | 6.63 ms: 1.12x faster                                  |
| scimark_sor             | 129 ms                                                 | 116 ms: 1.12x faster                                   |
| gunicorn                | 1.24 ms                                                | 1.13 ms: 1.10x faster                                  |
| aiohttp                 | 1.15 ms                                                | 1.05 ms: 1.10x faster                                  |
| float                   | 83.3 ms                                                | 76.0 ms: 1.10x faster                                  |
| pprint_safe_repr        | 765 ms                                                 | 700 ms: 1.09x faster                                   |
| scimark_monte_carlo     | 74.6 ms                                                | 68.4 ms: 1.09x faster                                  |
| logging_format          | 7.10 us                                                | 6.54 us: 1.08x faster                                  |
| dulwich_log             | 68.7 ms                                                | 63.5 ms: 1.08x faster                                  |
| regex_compile           | 148 ms                                                 | 137 ms: 1.08x faster                                   |
| regex_effbot            | 3.57 ms                                                | 3.31 ms: 1.08x faster                                  |
| pprint_pformat          | 1.55 sec                                               | 1.44 sec: 1.08x faster                                 |
| pickle_dict             | 33.5 us                                                | 31.1 us: 1.08x faster                                  |
| telco                   | 7.18 ms                                                | 6.66 ms: 1.08x faster                                  |
| docutils                | 2.75 sec                                               | 2.57 sec: 1.07x faster                                 |
| logging_simple          | 6.38 us                                                | 5.95 us: 1.07x faster                                  |
| deepcopy_memo           | 39.7 us                                                | 37.2 us: 1.07x faster                                  |
| fannkuch                | 410 ms                                                 | 384 ms: 1.07x faster                                   |
| 2to3                    | 274 ms                                                 | 258 ms: 1.06x faster                                   |
| logging_silent          | 108 ns                                                 | 102 ns: 1.05x faster                                   |
| django_template         | 35.0 ms                                                | 33.2 ms: 1.05x faster                                  |
| pickle_pure_python      | 326 us                                                 | 310 us: 1.05x faster                                   |
| raytrace                | 308 ms                                                 | 294 ms: 1.05x faster                                   |
| deepcopy_reduce         | 3.23 us                                                | 3.09 us: 1.04x faster                                  |
| pathlib                 | 18.9 ms                                                | 18.1 ms: 1.04x faster                                  |
| regex_dna               | 209 ms                                                 | 200 ms: 1.04x faster                                   |
| deepcopy                | 363 us                                                 | 349 us: 1.04x faster                                   |
| bench_thread_pool       | 845 us                                                 | 813 us: 1.04x faster                                   |
| sqlalchemy_declarative  | 147 ms                                                 | 141 ms: 1.04x faster                                   |
| meteor_contest          | 110 ms                                                 | 106 ms: 1.04x faster                                   |
| sqlalchemy_imperative   | 18.5 ms                                                | 18.0 ms: 1.03x faster                                  |
| sqlglot_normalize       | 112 ms                                                 | 108 ms: 1.03x faster                                   |
| sqlglot_optimize        | 54.8 ms                                                | 53.3 ms: 1.03x faster                                  |
| sympy_str               | 296 ms                                                 | 289 ms: 1.02x faster                                   |
| xml_etree_iterparse     | 106 ms                                                 | 103 ms: 1.02x faster                                   |
| unpickle_list           | 5.04 us                                                | 4.95 us: 1.02x faster                                  |
| regex_v8                | 22.7 ms                                                | 22.3 ms: 1.02x faster                                  |
| nqueens                 | 86.2 ms                                                | 85.0 ms: 1.01x faster                                  |
| hexiom                  | 6.54 ms                                                | 6.46 ms: 1.01x faster                                  |
| deltablue               | 3.71 ms                                                | 3.67 ms: 1.01x faster                                  |
| xml_etree_parse         | 159 ms                                                 | 158 ms: 1.01x faster                                   |
| sympy_integrate         | 21.2 ms                                                | 21.0 ms: 1.01x faster                                  |
| dask                    | 369 ms                                                 | 365 ms: 1.01x faster                                   |
| tornado_http            | 101 ms                                                 | 99.8 ms: 1.01x faster                                  |
| sympy_sum               | 167 ms                                                 | 166 ms: 1.01x faster                                   |
| sympy_expand            | 476 ms                                                 | 472 ms: 1.01x faster                                   |
| go                      | 140 ms                                                 | 140 ms: 1.01x faster                                   |
| gc_traversal            | 4.28 ms                                                | 4.26 ms: 1.01x faster                                  |
| unpickle_pure_python    | 230 us                                                 | 229 us: 1.00x faster                                   |
| pidigits                | 187 ms                                                 | 190 ms: 1.01x slower                                   |
| richards                | 46.0 ms                                                | 46.9 ms: 1.02x slower                                  |
| sqlglot_parse           | 1.35 ms                                                | 1.38 ms: 1.02x slower                                  |
| create_gc_cycles        | 1.45 ms                                                | 1.48 ms: 1.02x slower                                  |
| async_tree_cpu_io_mixed | 724 ms                                                 | 742 ms: 1.02x slower                                   |
| mdp                     | 2.57 sec                                               | 2.64 sec: 1.03x slower                                 |
| chaos                   | 67.5 ms                                                | 69.6 ms: 1.03x slower                                  |
| nbody                   | 92.2 ms                                                | 95.4 ms: 1.03x slower                                  |
| coroutines              | 23.5 ms                                                | 25.3 ms: 1.08x slower                                  |
| async_tree_memoization  | 580 ms                                                 | 627 ms: 1.08x slower                                   |
| async_tree_none         | 475 ms                                                 | 523 ms: 1.10x slower                                   |
| async_tree_io           | 1.16 sec                                               | 1.31 sec: 1.12x slower                                 |
| json_dumps              | 10.6 ms                                                | 12.6 ms: 1.19x slower                                  |
| mypy2                   | 351 ms                                                 | 421 ms: 1.20x slower                                   |
| coverage                | 75.1 ms                                                | 104 ms: 1.38x slower                                   |
| asyncio_tcp             | 506 ms                                                 | 889 ms: 1.76x slower                                   |
| generators              | 32.5 ms                                                | 73.3 ms: 2.26x slower                                  |
| Geometric mean          | (ref)                                                  | 1.03x faster                                           |

Benchmark hidden because not significant (3): pycparser, bench_mp_pool, sqlglot_transpile
Ignored benchmarks (10) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, comprehensions, richards_super, tomli_loads, typing_runtime_protocols
Ignored benchmarks (7) of results/bm-20221206-3.11.1-a7a450f/bm-20221206-linux-x86_64-python-v3.11.1-3.11.1-a7a450f.json: djangocms, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 99.99% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.01x
