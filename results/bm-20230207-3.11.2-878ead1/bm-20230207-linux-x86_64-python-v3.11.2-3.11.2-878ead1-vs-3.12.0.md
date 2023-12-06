
# Results vs. 3.12.0

- fork: python
- ref: v3.11.2
- machine: linux-x86_64
- commit hash: 878ead1
- commit date: 2023-02-07
- overall geometric mean: 1.03x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-linux-x86_64-python-v3.11.2-3.11.2-878ead1 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 257 ms: 1.07x faster                                   |
| chameleon      | 7.41 ms                                                | 6.49 ms: 1.14x faster                                  |
| docutils       | 2.75 sec                                               | 2.55 sec: 1.08x faster                                 |
| tornado_http   | 101 ms                                                 | 96.1 ms: 1.05x faster                                  |
| Geometric mean | (ref)                                                  | 1.08x faster                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-linux-x86_64-python-v3.11.2-3.11.2-878ead1 |
|-------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_tree_cpu_io_mixed | 724 ms                                                 | 740 ms: 1.02x slower                                   |
| async_tree_memoization  | 580 ms                                                 | 628 ms: 1.08x slower                                   |
| async_tree_none         | 475 ms                                                 | 524 ms: 1.10x slower                                   |
| async_tree_io           | 1.16 sec                                               | 1.30 sec: 1.11x slower                                 |
| Geometric mean          | (ref)                                                  | 1.08x slower                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-linux-x86_64-python-v3.11.2-3.11.2-878ead1 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| float          | 83.3 ms                                                | 76.6 ms: 1.09x faster                                  |
| nbody          | 92.2 ms                                                | 93.0 ms: 1.01x slower                                  |
| pidigits       | 187 ms                                                 | 190 ms: 1.01x slower                                   |
| Geometric mean | (ref)                                                  | 1.02x faster                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-linux-x86_64-python-v3.11.2-3.11.2-878ead1 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_dna      | 209 ms                                                 | 192 ms: 1.08x faster                                   |
| regex_compile  | 148 ms                                                 | 138 ms: 1.07x faster                                   |
| regex_v8       | 22.7 ms                                                | 21.3 ms: 1.06x faster                                  |
| regex_effbot   | 3.57 ms                                                | 3.39 ms: 1.05x faster                                  |
| Geometric mean | (ref)                                                  | 1.07x faster                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-linux-x86_64-python-v3.11.2-3.11.2-878ead1 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| unpickle             | 15.8 us                                                | 13.2 us: 1.19x faster                                  |
| xml_etree_generate   | 88.7 ms                                                | 76.5 ms: 1.16x faster                                  |
| xml_etree_process    | 61.2 ms                                                | 53.8 ms: 1.14x faster                                  |
| pickle_list          | 4.67 us                                                | 4.16 us: 1.12x faster                                  |
| pickle               | 11.2 us                                                | 10.00 us: 1.12x faster                                 |
| json_loads           | 28.4 us                                                | 26.2 us: 1.09x faster                                  |
| pickle_pure_python   | 326 us                                                 | 305 us: 1.07x faster                                   |
| pickle_dict          | 33.5 us                                                | 31.4 us: 1.07x faster                                  |
| unpickle_list        | 5.04 us                                                | 4.94 us: 1.02x faster                                  |
| xml_etree_iterparse  | 106 ms                                                 | 104 ms: 1.02x faster                                   |
| unpickle_pure_python | 230 us                                                 | 228 us: 1.01x faster                                   |
| json_dumps           | 10.6 ms                                                | 12.5 ms: 1.18x slower                                  |
| Geometric mean       | (ref)                                                  | 1.06x faster                                           |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-linux-x86_64-python-v3.11.2-3.11.2-878ead1 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup_no_site | 6.92 ms                                                | 5.97 ms: 1.16x faster                                  |
| python_startup         | 9.53 ms                                                | 8.47 ms: 1.13x faster                                  |
| Geometric mean         | (ref)                                                  | 1.14x faster                                           |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-linux-x86_64-python-v3.11.2-3.11.2-878ead1 |
|-----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako            | 11.5 ms                                                | 9.83 ms: 1.17x faster                                  |
| django_template | 35.0 ms                                                | 32.7 ms: 1.07x faster                                  |
| Geometric mean  | (ref)                                                  | 1.12x faster                                           |

All benchmarks:
===============

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-linux-x86_64-python-v3.11.2-3.11.2-878ead1 |
|-------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_generators        | 459 ms                                                 | 357 ms: 1.29x faster                                   |
| unpickle                | 15.8 us                                                | 13.2 us: 1.19x faster                                  |
| mako                    | 11.5 ms                                                | 9.83 ms: 1.17x faster                                  |
| spectral_norm           | 115 ms                                                 | 98.4 ms: 1.17x faster                                  |
| scimark_fft             | 381 ms                                                 | 327 ms: 1.16x faster                                   |
| xml_etree_generate      | 88.7 ms                                                | 76.5 ms: 1.16x faster                                  |
| python_startup_no_site  | 6.92 ms                                                | 5.97 ms: 1.16x faster                                  |
| scimark_sparse_mat_mult | 5.33 ms                                                | 4.63 ms: 1.15x faster                                  |
| sqlite_synth            | 2.83 us                                                | 2.46 us: 1.15x faster                                  |
| chameleon               | 7.41 ms                                                | 6.49 ms: 1.14x faster                                  |
| xml_etree_process       | 61.2 ms                                                | 53.8 ms: 1.14x faster                                  |
| crypto_pyaes            | 83.6 ms                                                | 73.8 ms: 1.13x faster                                  |
| pyflate                 | 471 ms                                                 | 417 ms: 1.13x faster                                   |
| scimark_sor             | 129 ms                                                 | 115 ms: 1.13x faster                                   |
| scimark_lu              | 120 ms                                                 | 107 ms: 1.13x faster                                   |
| python_startup          | 9.53 ms                                                | 8.47 ms: 1.13x faster                                  |
| pickle_list             | 4.67 us                                                | 4.16 us: 1.12x faster                                  |
| pickle                  | 11.2 us                                                | 10.00 us: 1.12x faster                                 |
| unpack_sequence         | 54.2 ns                                                | 48.8 ns: 1.11x faster                                  |
| scimark_monte_carlo     | 74.6 ms                                                | 67.7 ms: 1.10x faster                                  |
| aiohttp                 | 1.15 ms                                                | 1.05 ms: 1.10x faster                                  |
| gunicorn                | 1.24 ms                                                | 1.13 ms: 1.10x faster                                  |
| pprint_safe_repr        | 765 ms                                                 | 697 ms: 1.10x faster                                   |
| logging_format          | 7.10 us                                                | 6.49 us: 1.09x faster                                  |
| telco                   | 7.18 ms                                                | 6.59 ms: 1.09x faster                                  |
| float                   | 83.3 ms                                                | 76.6 ms: 1.09x faster                                  |
| json_loads              | 28.4 us                                                | 26.2 us: 1.09x faster                                  |
| regex_dna               | 209 ms                                                 | 192 ms: 1.08x faster                                   |
| deepcopy_memo           | 39.7 us                                                | 36.8 us: 1.08x faster                                  |
| docutils                | 2.75 sec                                               | 2.55 sec: 1.08x faster                                 |
| dulwich_log             | 68.7 ms                                                | 63.7 ms: 1.08x faster                                  |
| logging_silent          | 108 ns                                                 | 99.8 ns: 1.08x faster                                  |
| regex_compile           | 148 ms                                                 | 138 ms: 1.07x faster                                   |
| pprint_pformat          | 1.55 sec                                               | 1.45 sec: 1.07x faster                                 |
| django_template         | 35.0 ms                                                | 32.7 ms: 1.07x faster                                  |
| logging_simple          | 6.38 us                                                | 5.97 us: 1.07x faster                                  |
| pickle_pure_python      | 326 us                                                 | 305 us: 1.07x faster                                   |
| 2to3                    | 274 ms                                                 | 257 ms: 1.07x faster                                   |
| pickle_dict             | 33.5 us                                                | 31.4 us: 1.07x faster                                  |
| deepcopy_reduce         | 3.23 us                                                | 3.04 us: 1.06x faster                                  |
| regex_v8                | 22.7 ms                                                | 21.3 ms: 1.06x faster                                  |
| pathlib                 | 18.9 ms                                                | 17.8 ms: 1.06x faster                                  |
| json                    | 5.22 ms                                                | 4.92 ms: 1.06x faster                                  |
| raytrace                | 308 ms                                                 | 291 ms: 1.06x faster                                   |
| pycparser               | 1.17 sec                                               | 1.11 sec: 1.06x faster                                 |
| regex_effbot            | 3.57 ms                                                | 3.39 ms: 1.05x faster                                  |
| meteor_contest          | 110 ms                                                 | 105 ms: 1.05x faster                                   |
| tornado_http            | 101 ms                                                 | 96.1 ms: 1.05x faster                                  |
| fannkuch                | 410 ms                                                 | 392 ms: 1.05x faster                                   |
| deepcopy                | 363 us                                                 | 348 us: 1.04x faster                                   |
| bench_thread_pool       | 845 us                                                 | 812 us: 1.04x faster                                   |
| sqlalchemy_declarative  | 147 ms                                                 | 141 ms: 1.04x faster                                   |
| nqueens                 | 86.2 ms                                                | 83.1 ms: 1.04x faster                                  |
| gc_traversal            | 4.28 ms                                                | 4.15 ms: 1.03x faster                                  |
| sqlglot_optimize        | 54.8 ms                                                | 53.3 ms: 1.03x faster                                  |
| sympy_str               | 296 ms                                                 | 288 ms: 1.03x faster                                   |
| hexiom                  | 6.54 ms                                                | 6.36 ms: 1.03x faster                                  |
| sqlglot_normalize       | 112 ms                                                 | 109 ms: 1.03x faster                                   |
| unpickle_list           | 5.04 us                                                | 4.94 us: 1.02x faster                                  |
| sqlalchemy_imperative   | 18.5 ms                                                | 18.2 ms: 1.02x faster                                  |
| xml_etree_iterparse     | 106 ms                                                 | 104 ms: 1.02x faster                                   |
| sympy_integrate         | 21.2 ms                                                | 20.8 ms: 1.02x faster                                  |
| sympy_expand            | 476 ms                                                 | 468 ms: 1.02x faster                                   |
| dask                    | 369 ms                                                 | 365 ms: 1.01x faster                                   |
| sympy_sum               | 167 ms                                                 | 166 ms: 1.01x faster                                   |
| richards                | 46.0 ms                                                | 45.6 ms: 1.01x faster                                  |
| deltablue               | 3.71 ms                                                | 3.68 ms: 1.01x faster                                  |
| unpickle_pure_python    | 230 us                                                 | 228 us: 1.01x faster                                   |
| sqlglot_transpile       | 1.68 ms                                                | 1.67 ms: 1.01x faster                                  |
| go                      | 140 ms                                                 | 141 ms: 1.01x slower                                   |
| nbody                   | 92.2 ms                                                | 93.0 ms: 1.01x slower                                  |
| chaos                   | 67.5 ms                                                | 68.2 ms: 1.01x slower                                  |
| pidigits                | 187 ms                                                 | 190 ms: 1.01x slower                                   |
| sqlglot_parse           | 1.35 ms                                                | 1.38 ms: 1.02x slower                                  |
| async_tree_cpu_io_mixed | 724 ms                                                 | 740 ms: 1.02x slower                                   |
| create_gc_cycles        | 1.45 ms                                                | 1.49 ms: 1.02x slower                                  |
| mdp                     | 2.57 sec                                               | 2.77 sec: 1.08x slower                                 |
| async_tree_memoization  | 580 ms                                                 | 628 ms: 1.08x slower                                   |
| coroutines              | 23.5 ms                                                | 25.6 ms: 1.09x slower                                  |
| async_tree_none         | 475 ms                                                 | 524 ms: 1.10x slower                                   |
| async_tree_io           | 1.16 sec                                               | 1.30 sec: 1.11x slower                                 |
| json_dumps              | 10.6 ms                                                | 12.5 ms: 1.18x slower                                  |
| mypy2                   | 351 ms                                                 | 421 ms: 1.20x slower                                   |
| coverage                | 75.1 ms                                                | 103 ms: 1.37x slower                                   |
| asyncio_tcp             | 506 ms                                                 | 884 ms: 1.75x slower                                   |
| generators              | 32.5 ms                                                | 74.1 ms: 2.28x slower                                  |
| Geometric mean          | (ref)                                                  | 1.03x faster                                           |

Benchmark hidden because not significant (2): xml_etree_parse, bench_mp_pool
Ignored benchmarks (10) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, comprehensions, richards_super, tomli_loads, typing_runtime_protocols
Ignored benchmarks (7) of results/bm-20230207-3.11.2-878ead1/bm-20230207-linux-x86_64-python-v3.11.2-3.11.2-878ead1.json: djangocms, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.03x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.01x
