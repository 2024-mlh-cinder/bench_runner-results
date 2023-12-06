
# Results vs. 3.12.0

- fork: python
- ref: 3b9d793efcfd2c00c14f
- machine: linux-x86_64
- commit hash: 3b9d793
- commit date: 2022-11-14
- overall geometric mean: 1.07x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.05x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221114-linux-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 245 ms: 1.12x faster                                                  |
| chameleon      | 7.41 ms                                                | 6.30 ms: 1.18x faster                                                 |
| docutils       | 2.75 sec                                               | 2.50 sec: 1.10x faster                                                |
| tornado_http   | 101 ms                                                 | 93.1 ms: 1.08x faster                                                 |
| Geometric mean | (ref)                                                  | 1.12x faster                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221114-linux-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_none        | 475 ms                                                 | 527 ms: 1.11x slower                                                  |
| async_tree_memoization | 580 ms                                                 | 653 ms: 1.13x slower                                                  |
| async_tree_io          | 1.16 sec                                               | 1.32 sec: 1.13x slower                                                |
| Geometric mean         | (ref)                                                  | 1.09x slower                                                          |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221114-linux-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 83.3 ms                                                | 72.0 ms: 1.16x faster                                                 |
| pidigits       | 187 ms                                                 | 189 ms: 1.01x slower                                                  |
| nbody          | 92.2 ms                                                | 93.9 ms: 1.02x slower                                                 |
| Geometric mean | (ref)                                                  | 1.04x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221114-linux-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 127 ms: 1.17x faster                                                  |
| regex_v8       | 22.7 ms                                                | 21.1 ms: 1.08x faster                                                 |
| regex_effbot   | 3.57 ms                                                | 3.47 ms: 1.03x faster                                                 |
| regex_dna      | 209 ms                                                 | 208 ms: 1.00x faster                                                  |
| Geometric mean | (ref)                                                  | 1.07x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221114-linux-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| unpickle             | 15.8 us                                                | 12.9 us: 1.22x faster                                                 |
| json_loads           | 28.4 us                                                | 23.9 us: 1.19x faster                                                 |
| unpickle_pure_python | 230 us                                                 | 200 us: 1.15x faster                                                  |
| pickle_pure_python   | 326 us                                                 | 283 us: 1.15x faster                                                  |
| pickle_list          | 4.67 us                                                | 4.06 us: 1.15x faster                                                 |
| xml_etree_generate   | 88.7 ms                                                | 77.2 ms: 1.15x faster                                                 |
| xml_etree_process    | 61.2 ms                                                | 53.9 ms: 1.14x faster                                                 |
| pickle               | 11.2 us                                                | 9.88 us: 1.14x faster                                                 |
| json_dumps           | 10.6 ms                                                | 9.66 ms: 1.09x faster                                                 |
| pickle_dict          | 33.5 us                                                | 30.8 us: 1.09x faster                                                 |
| xml_etree_parse      | 159 ms                                                 | 149 ms: 1.07x faster                                                  |
| xml_etree_iterparse  | 106 ms                                                 | 103 ms: 1.03x faster                                                  |
| unpickle_list        | 5.04 us                                                | 4.98 us: 1.01x faster                                                 |
| Geometric mean       | (ref)                                                  | 1.12x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221114-linux-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 6.92 ms                                                | 6.12 ms: 1.13x faster                                                 |
| python_startup         | 9.53 ms                                                | 8.58 ms: 1.11x faster                                                 |
| Geometric mean         | (ref)                                                  | 1.12x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221114-linux-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|-----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 11.5 ms                                                | 9.39 ms: 1.22x faster                                                 |
| django_template | 35.0 ms                                                | 32.8 ms: 1.07x faster                                                 |
| Geometric mean  | (ref)                                                  | 1.14x faster                                                          |

All benchmarks:
===============

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221114-linux-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| scimark_sparse_mat_mult | 5.33 ms                                                | 4.00 ms: 1.33x faster                                                 |
| async_generators        | 459 ms                                                 | 355 ms: 1.29x faster                                                  |
| scimark_fft             | 381 ms                                                 | 309 ms: 1.23x faster                                                  |
| scimark_sor             | 129 ms                                                 | 105 ms: 1.23x faster                                                  |
| mako                    | 11.5 ms                                                | 9.39 ms: 1.22x faster                                                 |
| unpickle                | 15.8 us                                                | 12.9 us: 1.22x faster                                                 |
| spectral_norm           | 115 ms                                                 | 94.9 ms: 1.21x faster                                                 |
| json_loads              | 28.4 us                                                | 23.9 us: 1.19x faster                                                 |
| unpack_sequence         | 54.2 ns                                                | 45.7 ns: 1.19x faster                                                 |
| deepcopy_memo           | 39.7 us                                                | 33.6 us: 1.18x faster                                                 |
| chameleon               | 7.41 ms                                                | 6.30 ms: 1.18x faster                                                 |
| pyflate                 | 471 ms                                                 | 402 ms: 1.17x faster                                                  |
| regex_compile           | 148 ms                                                 | 127 ms: 1.17x faster                                                  |
| float                   | 83.3 ms                                                | 72.0 ms: 1.16x faster                                                 |
| aiohttp                 | 1.15 ms                                                | 999 us: 1.15x faster                                                  |
| deltablue               | 3.71 ms                                                | 3.22 ms: 1.15x faster                                                 |
| gunicorn                | 1.24 ms                                                | 1.08 ms: 1.15x faster                                                 |
| logging_silent          | 108 ns                                                 | 93.4 ns: 1.15x faster                                                 |
| unpickle_pure_python    | 230 us                                                 | 200 us: 1.15x faster                                                  |
| pickle_pure_python      | 326 us                                                 | 283 us: 1.15x faster                                                  |
| pickle_list             | 4.67 us                                                | 4.06 us: 1.15x faster                                                 |
| xml_etree_generate      | 88.7 ms                                                | 77.2 ms: 1.15x faster                                                 |
| xml_etree_process       | 61.2 ms                                                | 53.9 ms: 1.14x faster                                                 |
| pickle                  | 11.2 us                                                | 9.88 us: 1.14x faster                                                 |
| gc_traversal            | 4.28 ms                                                | 3.77 ms: 1.13x faster                                                 |
| python_startup_no_site  | 6.92 ms                                                | 6.12 ms: 1.13x faster                                                 |
| logging_format          | 7.10 us                                                | 6.30 us: 1.13x faster                                                 |
| telco                   | 7.18 ms                                                | 6.38 ms: 1.12x faster                                                 |
| json                    | 5.22 ms                                                | 4.65 ms: 1.12x faster                                                 |
| logging_simple          | 6.38 us                                                | 5.70 us: 1.12x faster                                                 |
| crypto_pyaes            | 83.6 ms                                                | 74.6 ms: 1.12x faster                                                 |
| 2to3                    | 274 ms                                                 | 245 ms: 1.12x faster                                                  |
| deepcopy_reduce         | 3.23 us                                                | 2.89 us: 1.12x faster                                                 |
| pprint_safe_repr        | 765 ms                                                 | 685 ms: 1.12x faster                                                  |
| pprint_pformat          | 1.55 sec                                               | 1.39 sec: 1.12x faster                                                |
| scimark_lu              | 120 ms                                                 | 108 ms: 1.11x faster                                                  |
| raytrace                | 308 ms                                                 | 277 ms: 1.11x faster                                                  |
| fannkuch                | 410 ms                                                 | 369 ms: 1.11x faster                                                  |
| dulwich_log             | 68.7 ms                                                | 61.8 ms: 1.11x faster                                                 |
| python_startup          | 9.53 ms                                                | 8.58 ms: 1.11x faster                                                 |
| deepcopy                | 363 us                                                 | 328 us: 1.11x faster                                                  |
| docutils                | 2.75 sec                                               | 2.50 sec: 1.10x faster                                                |
| richards                | 46.0 ms                                                | 41.8 ms: 1.10x faster                                                 |
| scimark_monte_carlo     | 74.6 ms                                                | 68.0 ms: 1.10x faster                                                 |
| json_dumps              | 10.6 ms                                                | 9.66 ms: 1.09x faster                                                 |
| pickle_dict             | 33.5 us                                                | 30.8 us: 1.09x faster                                                 |
| sqlite_synth            | 2.83 us                                                | 2.60 us: 1.09x faster                                                 |
| pycparser               | 1.17 sec                                               | 1.08 sec: 1.09x faster                                                |
| hexiom                  | 6.54 ms                                                | 6.04 ms: 1.08x faster                                                 |
| bench_thread_pool       | 845 us                                                 | 780 us: 1.08x faster                                                  |
| tornado_http            | 101 ms                                                 | 93.1 ms: 1.08x faster                                                 |
| mypy2                   | 351 ms                                                 | 325 ms: 1.08x faster                                                  |
| meteor_contest          | 110 ms                                                 | 102 ms: 1.08x faster                                                  |
| regex_v8                | 22.7 ms                                                | 21.1 ms: 1.08x faster                                                 |
| sqlglot_optimize        | 54.8 ms                                                | 51.0 ms: 1.07x faster                                                 |
| xml_etree_parse         | 159 ms                                                 | 149 ms: 1.07x faster                                                  |
| django_template         | 35.0 ms                                                | 32.8 ms: 1.07x faster                                                 |
| pathlib                 | 18.9 ms                                                | 17.7 ms: 1.07x faster                                                 |
| nqueens                 | 86.2 ms                                                | 81.1 ms: 1.06x faster                                                 |
| sqlglot_normalize       | 112 ms                                                 | 105 ms: 1.06x faster                                                  |
| sympy_str               | 296 ms                                                 | 282 ms: 1.05x faster                                                  |
| go                      | 140 ms                                                 | 135 ms: 1.04x faster                                                  |
| sympy_expand            | 476 ms                                                 | 456 ms: 1.04x faster                                                  |
| sympy_integrate         | 21.2 ms                                                | 20.4 ms: 1.04x faster                                                 |
| sqlglot_transpile       | 1.68 ms                                                | 1.62 ms: 1.04x faster                                                 |
| mdp                     | 2.57 sec                                               | 2.48 sec: 1.03x faster                                                |
| regex_effbot            | 3.57 ms                                                | 3.47 ms: 1.03x faster                                                 |
| chaos                   | 67.5 ms                                                | 65.8 ms: 1.03x faster                                                 |
| xml_etree_iterparse     | 106 ms                                                 | 103 ms: 1.03x faster                                                  |
| dask                    | 369 ms                                                 | 360 ms: 1.02x faster                                                  |
| sympy_sum               | 167 ms                                                 | 165 ms: 1.01x faster                                                  |
| sqlglot_parse           | 1.35 ms                                                | 1.33 ms: 1.01x faster                                                 |
| unpickle_list           | 5.04 us                                                | 4.98 us: 1.01x faster                                                 |
| regex_dna               | 209 ms                                                 | 208 ms: 1.00x faster                                                  |
| create_gc_cycles        | 1.45 ms                                                | 1.46 ms: 1.00x slower                                                 |
| pidigits                | 187 ms                                                 | 189 ms: 1.01x slower                                                  |
| nbody                   | 92.2 ms                                                | 93.9 ms: 1.02x slower                                                 |
| coroutines              | 23.5 ms                                                | 24.7 ms: 1.06x slower                                                 |
| async_tree_none         | 475 ms                                                 | 527 ms: 1.11x slower                                                  |
| comprehensions          | 20.9 us                                                | 23.4 us: 1.12x slower                                                 |
| async_tree_memoization  | 580 ms                                                 | 653 ms: 1.13x slower                                                  |
| async_tree_io           | 1.16 sec                                               | 1.32 sec: 1.13x slower                                                |
| coverage                | 75.1 ms                                                | 101 ms: 1.34x slower                                                  |
| asyncio_tcp             | 506 ms                                                 | 884 ms: 1.75x slower                                                  |
| generators              | 32.5 ms                                                | 77.4 ms: 2.38x slower                                                 |
| Geometric mean          | (ref)                                                  | 1.07x faster                                                          |

Benchmark hidden because not significant (2): bench_mp_pool, async_tree_cpu_io_mixed
Ignored benchmarks (11) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, typing_runtime_protocols
Ignored benchmarks (5) of results/bm-20221114-3.12.0a2-3b9d793/bm-20221114-linux-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793.json: djangocms, genshi_text, genshi_xml, html5lib, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.06x
- 95% likely to have a speedup of 1.06x
- 99% likely to have a speedup of 1.05x
