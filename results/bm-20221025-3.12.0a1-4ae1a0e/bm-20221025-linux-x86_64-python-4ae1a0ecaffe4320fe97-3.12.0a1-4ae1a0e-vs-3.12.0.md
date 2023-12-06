
# Results vs. 3.12.0

- fork: python
- ref: 4ae1a0ecaffe4320fe97
- machine: linux-x86_64
- commit hash: 4ae1a0e
- commit date: 2022-10-25
- overall geometric mean: 1.07x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.04x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221025-linux-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 249 ms: 1.10x faster                                                  |
| chameleon      | 7.41 ms                                                | 6.51 ms: 1.14x faster                                                 |
| docutils       | 2.75 sec                                               | 2.52 sec: 1.09x faster                                                |
| tornado_http   | 101 ms                                                 | 93.7 ms: 1.07x faster                                                 |
| Geometric mean | (ref)                                                  | 1.10x faster                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221025-linux-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_none        | 475 ms                                                 | 529 ms: 1.11x slower                                                  |
| async_tree_memoization | 580 ms                                                 | 656 ms: 1.13x slower                                                  |
| async_tree_io          | 1.16 sec                                               | 1.33 sec: 1.14x slower                                                |
| Geometric mean         | (ref)                                                  | 1.10x slower                                                          |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221025-linux-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 83.3 ms                                                | 71.4 ms: 1.17x faster                                                 |
| nbody          | 92.2 ms                                                | 96.6 ms: 1.05x slower                                                 |
| pidigits       | 187 ms                                                 | 198 ms: 1.06x slower                                                  |
| Geometric mean | (ref)                                                  | 1.02x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221025-linux-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 127 ms: 1.16x faster                                                  |
| regex_v8       | 22.7 ms                                                | 21.4 ms: 1.06x faster                                                 |
| regex_effbot   | 3.57 ms                                                | 3.37 ms: 1.06x faster                                                 |
| regex_dna      | 209 ms                                                 | 201 ms: 1.04x faster                                                  |
| Geometric mean | (ref)                                                  | 1.08x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221025-linux-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| json_loads           | 28.4 us                                                | 23.5 us: 1.21x faster                                                 |
| unpickle             | 15.8 us                                                | 13.2 us: 1.20x faster                                                 |
| xml_etree_generate   | 88.7 ms                                                | 76.0 ms: 1.17x faster                                                 |
| xml_etree_process    | 61.2 ms                                                | 53.4 ms: 1.15x faster                                                 |
| pickle_pure_python   | 326 us                                                 | 285 us: 1.14x faster                                                  |
| unpickle_pure_python | 230 us                                                 | 202 us: 1.14x faster                                                  |
| json_dumps           | 10.6 ms                                                | 9.36 ms: 1.13x faster                                                 |
| pickle_list          | 4.67 us                                                | 4.19 us: 1.11x faster                                                 |
| pickle               | 11.2 us                                                | 10.1 us: 1.11x faster                                                 |
| xml_etree_parse      | 159 ms                                                 | 145 ms: 1.10x faster                                                  |
| pickle_dict          | 33.5 us                                                | 31.1 us: 1.08x faster                                                 |
| xml_etree_iterparse  | 106 ms                                                 | 101 ms: 1.05x faster                                                  |
| unpickle_list        | 5.04 us                                                | 4.91 us: 1.03x faster                                                 |
| Geometric mean       | (ref)                                                  | 1.12x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221025-linux-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 6.92 ms                                                | 5.93 ms: 1.17x faster                                                 |
| python_startup         | 9.53 ms                                                | 8.42 ms: 1.13x faster                                                 |
| Geometric mean         | (ref)                                                  | 1.15x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221025-linux-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|-----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 11.5 ms                                                | 9.64 ms: 1.19x faster                                                 |
| django_template | 35.0 ms                                                | 33.0 ms: 1.06x faster                                                 |
| Geometric mean  | (ref)                                                  | 1.12x faster                                                          |

All benchmarks:
===============

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221025-linux-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_generators        | 459 ms                                                 | 349 ms: 1.32x faster                                                  |
| scimark_sparse_mat_mult | 5.33 ms                                                | 4.13 ms: 1.29x faster                                                 |
| unpack_sequence         | 54.2 ns                                                | 44.1 ns: 1.23x faster                                                 |
| scimark_sor             | 129 ms                                                 | 106 ms: 1.22x faster                                                  |
| scimark_fft             | 381 ms                                                 | 312 ms: 1.22x faster                                                  |
| json_loads              | 28.4 us                                                | 23.5 us: 1.21x faster                                                 |
| spectral_norm           | 115 ms                                                 | 95.2 ms: 1.21x faster                                                 |
| gc_traversal            | 4.28 ms                                                | 3.55 ms: 1.20x faster                                                 |
| unpickle                | 15.8 us                                                | 13.2 us: 1.20x faster                                                 |
| mako                    | 11.5 ms                                                | 9.64 ms: 1.19x faster                                                 |
| logging_silent          | 108 ns                                                 | 91.6 ns: 1.17x faster                                                 |
| xml_etree_generate      | 88.7 ms                                                | 76.0 ms: 1.17x faster                                                 |
| python_startup_no_site  | 6.92 ms                                                | 5.93 ms: 1.17x faster                                                 |
| float                   | 83.3 ms                                                | 71.4 ms: 1.17x faster                                                 |
| regex_compile           | 148 ms                                                 | 127 ms: 1.16x faster                                                  |
| gunicorn                | 1.24 ms                                                | 1.07 ms: 1.16x faster                                                 |
| pyflate                 | 471 ms                                                 | 407 ms: 1.16x faster                                                  |
| deepcopy_memo           | 39.7 us                                                | 34.4 us: 1.16x faster                                                 |
| pprint_safe_repr        | 765 ms                                                 | 665 ms: 1.15x faster                                                  |
| aiohttp                 | 1.15 ms                                                | 1.00 ms: 1.15x faster                                                 |
| xml_etree_process       | 61.2 ms                                                | 53.4 ms: 1.15x faster                                                 |
| json                    | 5.22 ms                                                | 4.55 ms: 1.15x faster                                                 |
| pickle_pure_python      | 326 us                                                 | 285 us: 1.14x faster                                                  |
| chameleon               | 7.41 ms                                                | 6.51 ms: 1.14x faster                                                 |
| unpickle_pure_python    | 230 us                                                 | 202 us: 1.14x faster                                                  |
| python_startup          | 9.53 ms                                                | 8.42 ms: 1.13x faster                                                 |
| json_dumps              | 10.6 ms                                                | 9.36 ms: 1.13x faster                                                 |
| pprint_pformat          | 1.55 sec                                               | 1.38 sec: 1.13x faster                                                |
| deltablue               | 3.71 ms                                                | 3.30 ms: 1.12x faster                                                 |
| scimark_monte_carlo     | 74.6 ms                                                | 66.6 ms: 1.12x faster                                                 |
| crypto_pyaes            | 83.6 ms                                                | 74.8 ms: 1.12x faster                                                 |
| pickle_list             | 4.67 us                                                | 4.19 us: 1.11x faster                                                 |
| logging_format          | 7.10 us                                                | 6.38 us: 1.11x faster                                                 |
| deepcopy_reduce         | 3.23 us                                                | 2.91 us: 1.11x faster                                                 |
| scimark_lu              | 120 ms                                                 | 108 ms: 1.11x faster                                                  |
| fannkuch                | 410 ms                                                 | 370 ms: 1.11x faster                                                  |
| pickle                  | 11.2 us                                                | 10.1 us: 1.11x faster                                                 |
| dulwich_log             | 68.7 ms                                                | 62.4 ms: 1.10x faster                                                 |
| logging_simple          | 6.38 us                                                | 5.80 us: 1.10x faster                                                 |
| 2to3                    | 274 ms                                                 | 249 ms: 1.10x faster                                                  |
| xml_etree_parse         | 159 ms                                                 | 145 ms: 1.10x faster                                                  |
| telco                   | 7.18 ms                                                | 6.55 ms: 1.09x faster                                                 |
| docutils                | 2.75 sec                                               | 2.52 sec: 1.09x faster                                                |
| deepcopy                | 363 us                                                 | 333 us: 1.09x faster                                                  |
| raytrace                | 308 ms                                                 | 282 ms: 1.09x faster                                                  |
| richards                | 46.0 ms                                                | 42.4 ms: 1.09x faster                                                 |
| bench_thread_pool       | 845 us                                                 | 780 us: 1.08x faster                                                  |
| sqlite_synth            | 2.83 us                                                | 2.62 us: 1.08x faster                                                 |
| pickle_dict             | 33.5 us                                                | 31.1 us: 1.08x faster                                                 |
| tornado_http            | 101 ms                                                 | 93.7 ms: 1.07x faster                                                 |
| hexiom                  | 6.54 ms                                                | 6.11 ms: 1.07x faster                                                 |
| sqlglot_optimize        | 54.8 ms                                                | 51.2 ms: 1.07x faster                                                 |
| sqlglot_normalize       | 112 ms                                                 | 104 ms: 1.07x faster                                                  |
| mypy2                   | 351 ms                                                 | 328 ms: 1.07x faster                                                  |
| nqueens                 | 86.2 ms                                                | 80.7 ms: 1.07x faster                                                 |
| django_template         | 35.0 ms                                                | 33.0 ms: 1.06x faster                                                 |
| regex_v8                | 22.7 ms                                                | 21.4 ms: 1.06x faster                                                 |
| regex_effbot            | 3.57 ms                                                | 3.37 ms: 1.06x faster                                                 |
| meteor_contest          | 110 ms                                                 | 104 ms: 1.05x faster                                                  |
| pathlib                 | 18.9 ms                                                | 17.9 ms: 1.05x faster                                                 |
| xml_etree_iterparse     | 106 ms                                                 | 101 ms: 1.05x faster                                                  |
| pycparser               | 1.17 sec                                               | 1.12 sec: 1.05x faster                                                |
| sympy_str               | 296 ms                                                 | 283 ms: 1.05x faster                                                  |
| sympy_expand            | 476 ms                                                 | 455 ms: 1.05x faster                                                  |
| go                      | 140 ms                                                 | 135 ms: 1.04x faster                                                  |
| sympy_integrate         | 21.2 ms                                                | 20.4 ms: 1.04x faster                                                 |
| regex_dna               | 209 ms                                                 | 201 ms: 1.04x faster                                                  |
| mdp                     | 2.57 sec                                               | 2.48 sec: 1.04x faster                                                |
| unpickle_list           | 5.04 us                                                | 4.91 us: 1.03x faster                                                 |
| sqlglot_transpile       | 1.68 ms                                                | 1.63 ms: 1.03x faster                                                 |
| dask                    | 369 ms                                                 | 360 ms: 1.03x faster                                                  |
| sympy_sum               | 167 ms                                                 | 164 ms: 1.02x faster                                                  |
| sqlglot_parse           | 1.35 ms                                                | 1.34 ms: 1.01x faster                                                 |
| chaos                   | 67.5 ms                                                | 67.1 ms: 1.01x faster                                                 |
| create_gc_cycles        | 1.45 ms                                                | 1.46 ms: 1.00x slower                                                 |
| comprehensions          | 20.9 us                                                | 21.3 us: 1.02x slower                                                 |
| nbody                   | 92.2 ms                                                | 96.6 ms: 1.05x slower                                                 |
| coroutines              | 23.5 ms                                                | 24.7 ms: 1.05x slower                                                 |
| pidigits                | 187 ms                                                 | 198 ms: 1.06x slower                                                  |
| async_tree_none         | 475 ms                                                 | 529 ms: 1.11x slower                                                  |
| async_tree_memoization  | 580 ms                                                 | 656 ms: 1.13x slower                                                  |
| async_tree_io           | 1.16 sec                                               | 1.33 sec: 1.14x slower                                                |
| coverage                | 75.1 ms                                                | 102 ms: 1.35x slower                                                  |
| asyncio_tcp             | 506 ms                                                 | 890 ms: 1.76x slower                                                  |
| generators              | 32.5 ms                                                | 74.1 ms: 2.28x slower                                                 |
| Geometric mean          | (ref)                                                  | 1.07x faster                                                          |

Benchmark hidden because not significant (2): bench_mp_pool, async_tree_cpu_io_mixed
Ignored benchmarks (11) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, typing_runtime_protocols
Ignored benchmarks (6) of results/bm-20221025-3.12.0a1-4ae1a0e/bm-20221025-linux-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e.json: djangocms, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.06x
- 95% likely to have a speedup of 1.05x
- 99% likely to have a speedup of 1.04x
