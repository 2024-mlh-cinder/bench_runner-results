
# Results vs. 3.12.0

- fork: python
- ref: b6bd7ffcbc1ffaa68e34
- machine: linux-x86_64
- commit hash: b6bd7ff
- commit date: 2022-12-06
- overall geometric mean: 1.06x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-linux-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 246 ms: 1.12x faster                                                  |
| chameleon      | 7.41 ms                                                | 6.45 ms: 1.15x faster                                                 |
| docutils       | 2.75 sec                                               | 2.57 sec: 1.07x faster                                                |
| Geometric mean | (ref)                                                  | 1.11x faster                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-linux-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 724 ms                                                 | 769 ms: 1.06x slower                                                  |
| async_tree_none         | 475 ms                                                 | 536 ms: 1.13x slower                                                  |
| async_tree_memoization  | 580 ms                                                 | 665 ms: 1.15x slower                                                  |
| async_tree_io           | 1.16 sec                                               | 1.34 sec: 1.15x slower                                                |
| Geometric mean          | (ref)                                                  | 1.12x slower                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-linux-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 83.3 ms                                                | 73.2 ms: 1.14x faster                                                 |
| pidigits       | 187 ms                                                 | 189 ms: 1.01x slower                                                  |
| nbody          | 92.2 ms                                                | 94.0 ms: 1.02x slower                                                 |
| Geometric mean | (ref)                                                  | 1.03x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-linux-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 129 ms: 1.15x faster                                                  |
| regex_v8       | 22.7 ms                                                | 22.3 ms: 1.01x faster                                                 |
| regex_effbot   | 3.57 ms                                                | 3.63 ms: 1.02x slower                                                 |
| regex_dna      | 209 ms                                                 | 217 ms: 1.04x slower                                                  |
| Geometric mean | (ref)                                                  | 1.02x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-linux-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| json_loads           | 28.4 us                                                | 23.8 us: 1.19x faster                                                 |
| pickle_list          | 4.67 us                                                | 3.95 us: 1.18x faster                                                 |
| unpickle             | 15.8 us                                                | 13.3 us: 1.18x faster                                                 |
| pickle_pure_python   | 326 us                                                 | 282 us: 1.15x faster                                                  |
| xml_etree_generate   | 88.7 ms                                                | 76.9 ms: 1.15x faster                                                 |
| unpickle_pure_python | 230 us                                                 | 200 us: 1.15x faster                                                  |
| xml_etree_process    | 61.2 ms                                                | 53.7 ms: 1.14x faster                                                 |
| json_dumps           | 10.6 ms                                                | 9.52 ms: 1.11x faster                                                 |
| pickle               | 11.2 us                                                | 10.1 us: 1.11x faster                                                 |
| xml_etree_parse      | 159 ms                                                 | 148 ms: 1.08x faster                                                  |
| pickle_dict          | 33.5 us                                                | 31.5 us: 1.06x faster                                                 |
| unpickle_list        | 5.04 us                                                | 4.97 us: 1.02x faster                                                 |
| xml_etree_iterparse  | 106 ms                                                 | 104 ms: 1.01x faster                                                  |
| Geometric mean       | (ref)                                                  | 1.12x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-linux-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 6.92 ms                                                | 6.07 ms: 1.14x faster                                                 |
| python_startup         | 9.53 ms                                                | 8.52 ms: 1.12x faster                                                 |
| Geometric mean         | (ref)                                                  | 1.13x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-linux-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|-----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 11.5 ms                                                | 9.43 ms: 1.22x faster                                                 |
| django_template | 35.0 ms                                                | 33.0 ms: 1.06x faster                                                 |
| Geometric mean  | (ref)                                                  | 1.14x faster                                                          |

All benchmarks:
===============

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-linux-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_generators        | 459 ms                                                 | 354 ms: 1.30x faster                                                  |
| scimark_sparse_mat_mult | 5.33 ms                                                | 4.20 ms: 1.27x faster                                                 |
| unpack_sequence         | 54.2 ns                                                | 43.1 ns: 1.26x faster                                                 |
| scimark_sor             | 129 ms                                                 | 105 ms: 1.23x faster                                                  |
| mako                    | 11.5 ms                                                | 9.43 ms: 1.22x faster                                                 |
| scimark_fft             | 381 ms                                                 | 314 ms: 1.21x faster                                                  |
| spectral_norm           | 115 ms                                                 | 96.0 ms: 1.20x faster                                                 |
| json_loads              | 28.4 us                                                | 23.8 us: 1.19x faster                                                 |
| pickle_list             | 4.67 us                                                | 3.95 us: 1.18x faster                                                 |
| logging_silent          | 108 ns                                                 | 90.9 ns: 1.18x faster                                                 |
| unpickle                | 15.8 us                                                | 13.3 us: 1.18x faster                                                 |
| pyflate                 | 471 ms                                                 | 405 ms: 1.16x faster                                                  |
| deepcopy_memo           | 39.7 us                                                | 34.2 us: 1.16x faster                                                 |
| pickle_pure_python      | 326 us                                                 | 282 us: 1.15x faster                                                  |
| xml_etree_generate      | 88.7 ms                                                | 76.9 ms: 1.15x faster                                                 |
| deltablue               | 3.71 ms                                                | 3.22 ms: 1.15x faster                                                 |
| regex_compile           | 148 ms                                                 | 129 ms: 1.15x faster                                                  |
| chameleon               | 7.41 ms                                                | 6.45 ms: 1.15x faster                                                 |
| unpickle_pure_python    | 230 us                                                 | 200 us: 1.15x faster                                                  |
| scimark_monte_carlo     | 74.6 ms                                                | 65.4 ms: 1.14x faster                                                 |
| xml_etree_process       | 61.2 ms                                                | 53.7 ms: 1.14x faster                                                 |
| python_startup_no_site  | 6.92 ms                                                | 6.07 ms: 1.14x faster                                                 |
| float                   | 83.3 ms                                                | 73.2 ms: 1.14x faster                                                 |
| scimark_lu              | 120 ms                                                 | 106 ms: 1.13x faster                                                  |
| gc_traversal            | 4.28 ms                                                | 3.81 ms: 1.12x faster                                                 |
| python_startup          | 9.53 ms                                                | 8.52 ms: 1.12x faster                                                 |
| json                    | 5.22 ms                                                | 4.67 ms: 1.12x faster                                                 |
| 2to3                    | 274 ms                                                 | 246 ms: 1.12x faster                                                  |
| pprint_safe_repr        | 765 ms                                                 | 686 ms: 1.12x faster                                                  |
| telco                   | 7.18 ms                                                | 6.46 ms: 1.11x faster                                                 |
| crypto_pyaes            | 83.6 ms                                                | 75.3 ms: 1.11x faster                                                 |
| json_dumps              | 10.6 ms                                                | 9.52 ms: 1.11x faster                                                 |
| logging_format          | 7.10 us                                                | 6.41 us: 1.11x faster                                                 |
| pickle                  | 11.2 us                                                | 10.1 us: 1.11x faster                                                 |
| dulwich_log             | 68.7 ms                                                | 62.5 ms: 1.10x faster                                                 |
| sqlite_synth            | 2.83 us                                                | 2.58 us: 1.10x faster                                                 |
| pprint_pformat          | 1.55 sec                                               | 1.41 sec: 1.10x faster                                                |
| raytrace                | 308 ms                                                 | 281 ms: 1.10x faster                                                  |
| richards                | 46.0 ms                                                | 42.0 ms: 1.10x faster                                                 |
| deepcopy                | 363 us                                                 | 332 us: 1.09x faster                                                  |
| deepcopy_reduce         | 3.23 us                                                | 2.97 us: 1.09x faster                                                 |
| logging_simple          | 6.38 us                                                | 5.88 us: 1.09x faster                                                 |
| bench_thread_pool       | 845 us                                                 | 778 us: 1.09x faster                                                  |
| fannkuch                | 410 ms                                                 | 379 ms: 1.08x faster                                                  |
| sqlglot_optimize        | 54.8 ms                                                | 50.6 ms: 1.08x faster                                                 |
| nqueens                 | 86.2 ms                                                | 80.1 ms: 1.08x faster                                                 |
| hexiom                  | 6.54 ms                                                | 6.08 ms: 1.08x faster                                                 |
| xml_etree_parse         | 159 ms                                                 | 148 ms: 1.08x faster                                                  |
| pycparser               | 1.17 sec                                               | 1.09 sec: 1.07x faster                                                |
| docutils                | 2.75 sec                                               | 2.57 sec: 1.07x faster                                                |
| mypy2                   | 351 ms                                                 | 329 ms: 1.07x faster                                                  |
| sqlglot_normalize       | 112 ms                                                 | 105 ms: 1.07x faster                                                  |
| pickle_dict             | 33.5 us                                                | 31.5 us: 1.06x faster                                                 |
| django_template         | 35.0 ms                                                | 33.0 ms: 1.06x faster                                                 |
| meteor_contest          | 110 ms                                                 | 104 ms: 1.06x faster                                                  |
| sympy_str               | 296 ms                                                 | 283 ms: 1.05x faster                                                  |
| sympy_expand            | 476 ms                                                 | 458 ms: 1.04x faster                                                  |
| sympy_integrate         | 21.2 ms                                                | 20.4 ms: 1.04x faster                                                 |
| go                      | 140 ms                                                 | 136 ms: 1.04x faster                                                  |
| pathlib                 | 18.9 ms                                                | 18.3 ms: 1.03x faster                                                 |
| mdp                     | 2.57 sec                                               | 2.50 sec: 1.03x faster                                                |
| sqlglot_transpile       | 1.68 ms                                                | 1.63 ms: 1.03x faster                                                 |
| dask                    | 369 ms                                                 | 360 ms: 1.02x faster                                                  |
| sympy_sum               | 167 ms                                                 | 164 ms: 1.02x faster                                                  |
| unpickle_list           | 5.04 us                                                | 4.97 us: 1.02x faster                                                 |
| regex_v8                | 22.7 ms                                                | 22.3 ms: 1.01x faster                                                 |
| xml_etree_iterparse     | 106 ms                                                 | 104 ms: 1.01x faster                                                  |
| chaos                   | 67.5 ms                                                | 66.9 ms: 1.01x faster                                                 |
| create_gc_cycles        | 1.45 ms                                                | 1.44 ms: 1.01x faster                                                 |
| sqlglot_parse           | 1.35 ms                                                | 1.34 ms: 1.00x faster                                                 |
| pidigits                | 187 ms                                                 | 189 ms: 1.01x slower                                                  |
| regex_effbot            | 3.57 ms                                                | 3.63 ms: 1.02x slower                                                 |
| nbody                   | 92.2 ms                                                | 94.0 ms: 1.02x slower                                                 |
| regex_dna               | 209 ms                                                 | 217 ms: 1.04x slower                                                  |
| async_tree_cpu_io_mixed | 724 ms                                                 | 769 ms: 1.06x slower                                                  |
| coroutines              | 23.5 ms                                                | 25.0 ms: 1.06x slower                                                 |
| comprehensions          | 20.9 us                                                | 23.5 us: 1.12x slower                                                 |
| async_tree_none         | 475 ms                                                 | 536 ms: 1.13x slower                                                  |
| async_tree_memoization  | 580 ms                                                 | 665 ms: 1.15x slower                                                  |
| async_tree_io           | 1.16 sec                                               | 1.34 sec: 1.15x slower                                                |
| coverage                | 75.1 ms                                                | 102 ms: 1.36x slower                                                  |
| asyncio_tcp             | 506 ms                                                 | 890 ms: 1.76x slower                                                  |
| generators              | 32.5 ms                                                | 79.1 ms: 2.44x slower                                                 |
| Geometric mean          | (ref)                                                  | 1.06x faster                                                          |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (14) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, gunicorn, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, tornado_http, typing_runtime_protocols
Ignored benchmarks (5) of results/bm-20221206-3.12.0a3-b6bd7ff/bm-20221206-linux-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff.json: djangocms, genshi_text, genshi_xml, html5lib, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.05x
- 95% likely to have a speedup of 1.04x
- 99% likely to have a speedup of 1.03x
