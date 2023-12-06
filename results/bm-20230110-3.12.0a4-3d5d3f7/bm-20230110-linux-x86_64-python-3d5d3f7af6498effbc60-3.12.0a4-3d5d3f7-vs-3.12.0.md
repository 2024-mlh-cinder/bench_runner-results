
# Results vs. 3.12.0

- fork: python
- ref: 3d5d3f7af6498effbc60
- machine: linux-x86_64
- commit hash: 3d5d3f7
- commit date: 2023-01-10
- overall geometric mean: 1.07x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.04x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230110-linux-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 253 ms: 1.09x faster                                                  |
| chameleon      | 7.41 ms                                                | 6.46 ms: 1.15x faster                                                 |
| docutils       | 2.75 sec                                               | 2.48 sec: 1.11x faster                                                |
| Geometric mean | (ref)                                                  | 1.11x faster                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230110-linux-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 724 ms                                                 | 747 ms: 1.03x slower                                                  |
| async_tree_memoization  | 580 ms                                                 | 616 ms: 1.06x slower                                                  |
| async_tree_none         | 475 ms                                                 | 521 ms: 1.10x slower                                                  |
| async_tree_io           | 1.16 sec                                               | 1.30 sec: 1.11x slower                                                |
| Geometric mean          | (ref)                                                  | 1.08x slower                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230110-linux-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 83.3 ms                                                | 72.2 ms: 1.15x faster                                                 |
| nbody          | 92.2 ms                                                | 93.1 ms: 1.01x slower                                                 |
| pidigits       | 187 ms                                                 | 192 ms: 1.03x slower                                                  |
| Geometric mean | (ref)                                                  | 1.04x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230110-linux-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 132 ms: 1.12x faster                                                  |
| regex_v8       | 22.7 ms                                                | 21.1 ms: 1.08x faster                                                 |
| regex_effbot   | 3.57 ms                                                | 3.49 ms: 1.02x faster                                                 |
| Geometric mean | (ref)                                                  | 1.05x faster                                                          |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230110-linux-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| unpickle             | 15.8 us                                                | 13.0 us: 1.22x faster                                                 |
| json_loads           | 28.4 us                                                | 24.3 us: 1.17x faster                                                 |
| pickle_list          | 4.67 us                                                | 4.02 us: 1.16x faster                                                 |
| unpickle_pure_python | 230 us                                                 | 200 us: 1.15x faster                                                  |
| xml_etree_generate   | 88.7 ms                                                | 77.5 ms: 1.15x faster                                                 |
| pickle_pure_python   | 326 us                                                 | 285 us: 1.14x faster                                                  |
| xml_etree_process    | 61.2 ms                                                | 53.9 ms: 1.14x faster                                                 |
| pickle               | 11.2 us                                                | 10.0 us: 1.12x faster                                                 |
| pickle_dict          | 33.5 us                                                | 30.0 us: 1.12x faster                                                 |
| json_dumps           | 10.6 ms                                                | 9.54 ms: 1.11x faster                                                 |
| xml_etree_parse      | 159 ms                                                 | 149 ms: 1.07x faster                                                  |
| unpickle_list        | 5.04 us                                                | 4.96 us: 1.02x faster                                                 |
| xml_etree_iterparse  | 106 ms                                                 | 106 ms: 1.01x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.12x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230110-linux-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 6.92 ms                                                | 6.09 ms: 1.14x faster                                                 |
| python_startup         | 9.53 ms                                                | 8.54 ms: 1.12x faster                                                 |
| Geometric mean         | (ref)                                                  | 1.13x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230110-linux-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|-----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 11.5 ms                                                | 9.74 ms: 1.18x faster                                                 |
| django_template | 35.0 ms                                                | 32.6 ms: 1.08x faster                                                 |
| Geometric mean  | (ref)                                                  | 1.13x faster                                                          |

All benchmarks:
===============

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230110-linux-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| unpack_sequence         | 54.2 ns                                                | 41.4 ns: 1.31x faster                                                 |
| async_generators        | 459 ms                                                 | 354 ms: 1.30x faster                                                  |
| scimark_sparse_mat_mult | 5.33 ms                                                | 4.13 ms: 1.29x faster                                                 |
| unpickle                | 15.8 us                                                | 13.0 us: 1.22x faster                                                 |
| scimark_fft             | 381 ms                                                 | 314 ms: 1.21x faster                                                  |
| spectral_norm           | 115 ms                                                 | 95.0 ms: 1.21x faster                                                 |
| gc_traversal            | 4.28 ms                                                | 3.57 ms: 1.20x faster                                                 |
| scimark_sor             | 129 ms                                                 | 108 ms: 1.19x faster                                                  |
| pyflate                 | 471 ms                                                 | 397 ms: 1.19x faster                                                  |
| mako                    | 11.5 ms                                                | 9.74 ms: 1.18x faster                                                 |
| json_loads              | 28.4 us                                                | 24.3 us: 1.17x faster                                                 |
| pickle_list             | 4.67 us                                                | 4.02 us: 1.16x faster                                                 |
| float                   | 83.3 ms                                                | 72.2 ms: 1.15x faster                                                 |
| logging_silent          | 108 ns                                                 | 93.5 ns: 1.15x faster                                                 |
| unpickle_pure_python    | 230 us                                                 | 200 us: 1.15x faster                                                  |
| chameleon               | 7.41 ms                                                | 6.46 ms: 1.15x faster                                                 |
| telco                   | 7.18 ms                                                | 6.26 ms: 1.15x faster                                                 |
| xml_etree_generate      | 88.7 ms                                                | 77.5 ms: 1.15x faster                                                 |
| deepcopy_memo           | 39.7 us                                                | 34.7 us: 1.15x faster                                                 |
| pickle_pure_python      | 326 us                                                 | 285 us: 1.14x faster                                                  |
| deltablue               | 3.71 ms                                                | 3.25 ms: 1.14x faster                                                 |
| scimark_monte_carlo     | 74.6 ms                                                | 65.7 ms: 1.14x faster                                                 |
| xml_etree_process       | 61.2 ms                                                | 53.9 ms: 1.14x faster                                                 |
| python_startup_no_site  | 6.92 ms                                                | 6.09 ms: 1.14x faster                                                 |
| fannkuch                | 410 ms                                                 | 362 ms: 1.13x faster                                                  |
| pprint_safe_repr        | 765 ms                                                 | 680 ms: 1.12x faster                                                  |
| regex_compile           | 148 ms                                                 | 132 ms: 1.12x faster                                                  |
| pprint_pformat          | 1.55 sec                                               | 1.38 sec: 1.12x faster                                                |
| scimark_lu              | 120 ms                                                 | 107 ms: 1.12x faster                                                  |
| pickle                  | 11.2 us                                                | 10.0 us: 1.12x faster                                                 |
| pickle_dict             | 33.5 us                                                | 30.0 us: 1.12x faster                                                 |
| logging_format          | 7.10 us                                                | 6.35 us: 1.12x faster                                                 |
| python_startup          | 9.53 ms                                                | 8.54 ms: 1.12x faster                                                 |
| docutils                | 2.75 sec                                               | 2.48 sec: 1.11x faster                                                |
| json_dumps              | 10.6 ms                                                | 9.54 ms: 1.11x faster                                                 |
| dulwich_log             | 68.7 ms                                                | 62.1 ms: 1.11x faster                                                 |
| logging_simple          | 6.38 us                                                | 5.77 us: 1.11x faster                                                 |
| nqueens                 | 86.2 ms                                                | 78.0 ms: 1.11x faster                                                 |
| crypto_pyaes            | 83.6 ms                                                | 75.7 ms: 1.10x faster                                                 |
| sqlite_synth            | 2.83 us                                                | 2.57 us: 1.10x faster                                                 |
| json                    | 5.22 ms                                                | 4.74 ms: 1.10x faster                                                 |
| hexiom                  | 6.54 ms                                                | 5.98 ms: 1.09x faster                                                 |
| richards                | 46.0 ms                                                | 42.3 ms: 1.09x faster                                                 |
| 2to3                    | 274 ms                                                 | 253 ms: 1.09x faster                                                  |
| raytrace                | 308 ms                                                 | 284 ms: 1.09x faster                                                  |
| pycparser               | 1.17 sec                                               | 1.08 sec: 1.08x faster                                                |
| bench_thread_pool       | 845 us                                                 | 782 us: 1.08x faster                                                  |
| sqlglot_optimize        | 54.8 ms                                                | 50.7 ms: 1.08x faster                                                 |
| deepcopy_reduce         | 3.23 us                                                | 2.99 us: 1.08x faster                                                 |
| django_template         | 35.0 ms                                                | 32.6 ms: 1.08x faster                                                 |
| regex_v8                | 22.7 ms                                                | 21.1 ms: 1.08x faster                                                 |
| sqlglot_normalize       | 112 ms                                                 | 104 ms: 1.07x faster                                                  |
| deepcopy                | 363 us                                                 | 339 us: 1.07x faster                                                  |
| xml_etree_parse         | 159 ms                                                 | 149 ms: 1.07x faster                                                  |
| mypy2                   | 351 ms                                                 | 332 ms: 1.06x faster                                                  |
| meteor_contest          | 110 ms                                                 | 104 ms: 1.05x faster                                                  |
| sympy_str               | 296 ms                                                 | 282 ms: 1.05x faster                                                  |
| pathlib                 | 18.9 ms                                                | 18.0 ms: 1.05x faster                                                 |
| sympy_expand            | 476 ms                                                 | 455 ms: 1.05x faster                                                  |
| sympy_integrate         | 21.2 ms                                                | 20.3 ms: 1.04x faster                                                 |
| dask                    | 369 ms                                                 | 355 ms: 1.04x faster                                                  |
| go                      | 140 ms                                                 | 135 ms: 1.04x faster                                                  |
| sympy_sum               | 167 ms                                                 | 163 ms: 1.03x faster                                                  |
| regex_effbot            | 3.57 ms                                                | 3.49 ms: 1.02x faster                                                 |
| unpickle_list           | 5.04 us                                                | 4.96 us: 1.02x faster                                                 |
| asyncio_tcp             | 506 ms                                                 | 504 ms: 1.00x faster                                                  |
| xml_etree_iterparse     | 106 ms                                                 | 106 ms: 1.01x slower                                                  |
| nbody                   | 92.2 ms                                                | 93.1 ms: 1.01x slower                                                 |
| sqlglot_transpile       | 1.68 ms                                                | 1.69 ms: 1.01x slower                                                 |
| pidigits                | 187 ms                                                 | 192 ms: 1.03x slower                                                  |
| async_tree_cpu_io_mixed | 724 ms                                                 | 747 ms: 1.03x slower                                                  |
| mdp                     | 2.57 sec                                               | 2.66 sec: 1.03x slower                                                |
| sqlglot_parse           | 1.35 ms                                                | 1.41 ms: 1.04x slower                                                 |
| async_tree_memoization  | 580 ms                                                 | 616 ms: 1.06x slower                                                  |
| coroutines              | 23.5 ms                                                | 25.4 ms: 1.08x slower                                                 |
| async_tree_none         | 475 ms                                                 | 521 ms: 1.10x slower                                                  |
| async_tree_io           | 1.16 sec                                               | 1.30 sec: 1.11x slower                                                |
| comprehensions          | 20.9 us                                                | 23.7 us: 1.13x slower                                                 |
| coverage                | 75.1 ms                                                | 99.0 ms: 1.32x slower                                                 |
| generators              | 32.5 ms                                                | 79.1 ms: 2.44x slower                                                 |
| Geometric mean          | (ref)                                                  | 1.07x faster                                                          |

Benchmark hidden because not significant (4): bench_mp_pool, regex_dna, create_gc_cycles, chaos
Ignored benchmarks (14) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, gunicorn, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, tornado_http, typing_runtime_protocols
Ignored benchmarks (5) of results/bm-20230110-3.12.0a4-3d5d3f7/bm-20230110-linux-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7.json: djangocms, genshi_text, genshi_xml, html5lib, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.06x
- 95% likely to have a speedup of 1.05x
- 99% likely to have a speedup of 1.04x
