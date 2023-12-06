
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 9471106
- commit date: 2022-01-13
- overall geometric mean: 1.03x faster \*
- HPT reliability: 82.46%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220113-linux-x86_64-python-main-3.11.0a4-9471106 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| 2to3           | 274 ms                                                 | 264 ms: 1.04x faster                                  |
| chameleon      | 7.41 ms                                                | 7.55 ms: 1.02x slower                                 |
| tornado_http   | 101 ms                                                 | 107 ms: 1.06x slower                                  |
| Geometric mean | (ref)                                                  | 1.01x slower                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220113-linux-x86_64-python-main-3.11.0a4-9471106 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| float          | 83.3 ms                                                | 78.0 ms: 1.07x faster                                 |
| nbody          | 92.2 ms                                                | 95.1 ms: 1.03x slower                                 |
| pidigits       | 187 ms                                                 | 194 ms: 1.04x slower                                  |
| Geometric mean | (ref)                                                  | 1.00x slower                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220113-linux-x86_64-python-main-3.11.0a4-9471106 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_effbot   | 3.57 ms                                                | 3.25 ms: 1.10x faster                                 |
| regex_compile  | 148 ms                                                 | 138 ms: 1.07x faster                                  |
| regex_dna      | 209 ms                                                 | 212 ms: 1.02x slower                                  |
| regex_v8       | 22.7 ms                                                | 24.8 ms: 1.10x slower                                 |
| Geometric mean | (ref)                                                  | 1.01x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220113-linux-x86_64-python-main-3.11.0a4-9471106 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_dict          | 33.5 us                                                | 26.8 us: 1.25x faster                                 |
| json_loads           | 28.4 us                                                | 25.1 us: 1.13x faster                                 |
| pickle               | 11.2 us                                                | 9.95 us: 1.13x faster                                 |
| xml_etree_generate   | 88.7 ms                                                | 80.2 ms: 1.11x faster                                 |
| unpickle             | 15.8 us                                                | 14.3 us: 1.10x faster                                 |
| xml_etree_process    | 61.2 ms                                                | 56.9 ms: 1.08x faster                                 |
| pickle_list          | 4.67 us                                                | 4.37 us: 1.07x faster                                 |
| xml_etree_parse      | 159 ms                                                 | 155 ms: 1.03x faster                                  |
| pickle_pure_python   | 326 us                                                 | 329 us: 1.01x slower                                  |
| xml_etree_iterparse  | 106 ms                                                 | 107 ms: 1.02x slower                                  |
| unpickle_list        | 5.04 us                                                | 5.20 us: 1.03x slower                                 |
| unpickle_pure_python | 230 us                                                 | 254 us: 1.10x slower                                  |
| json_dumps           | 10.6 ms                                                | 12.4 ms: 1.17x slower                                 |
| Geometric mean       | (ref)                                                  | 1.04x faster                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220113-linux-x86_64-python-main-3.11.0a4-9471106 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup_no_site | 6.92 ms                                                | 5.85 ms: 1.18x faster                                 |
| python_startup         | 9.53 ms                                                | 8.07 ms: 1.18x faster                                 |
| Geometric mean         | (ref)                                                  | 1.18x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220113-linux-x86_64-python-main-3.11.0a4-9471106 |
|-----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako            | 11.5 ms                                                | 11.5 ms: 1.00x slower                                 |
| django_template | 35.0 ms                                                | 35.2 ms: 1.01x slower                                 |
| Geometric mean  | (ref)                                                  | 1.00x slower                                          |

All benchmarks:
===============

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220113-linux-x86_64-python-main-3.11.0a4-9471106 |
|-------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_dict             | 33.5 us                                                | 26.8 us: 1.25x faster                                 |
| unpack_sequence         | 54.2 ns                                                | 44.8 ns: 1.21x faster                                 |
| python_startup_no_site  | 6.92 ms                                                | 5.85 ms: 1.18x faster                                 |
| python_startup          | 9.53 ms                                                | 8.07 ms: 1.18x faster                                 |
| spectral_norm           | 115 ms                                                 | 99.0 ms: 1.16x faster                                 |
| scimark_fft             | 381 ms                                                 | 330 ms: 1.16x faster                                  |
| scimark_sparse_mat_mult | 5.33 ms                                                | 4.69 ms: 1.14x faster                                 |
| json_loads              | 28.4 us                                                | 25.1 us: 1.13x faster                                 |
| pickle                  | 11.2 us                                                | 9.95 us: 1.13x faster                                 |
| xml_etree_generate      | 88.7 ms                                                | 80.2 ms: 1.11x faster                                 |
| unpickle                | 15.8 us                                                | 14.3 us: 1.10x faster                                 |
| json                    | 5.22 ms                                                | 4.74 ms: 1.10x faster                                 |
| regex_effbot            | 3.57 ms                                                | 3.25 ms: 1.10x faster                                 |
| logging_format          | 7.10 us                                                | 6.51 us: 1.09x faster                                 |
| xml_etree_process       | 61.2 ms                                                | 56.9 ms: 1.08x faster                                 |
| logging_simple          | 6.38 us                                                | 5.95 us: 1.07x faster                                 |
| telco                   | 7.18 ms                                                | 6.69 ms: 1.07x faster                                 |
| regex_compile           | 148 ms                                                 | 138 ms: 1.07x faster                                  |
| pickle_list             | 4.67 us                                                | 4.37 us: 1.07x faster                                 |
| meteor_contest          | 110 ms                                                 | 103 ms: 1.07x faster                                  |
| float                   | 83.3 ms                                                | 78.0 ms: 1.07x faster                                 |
| pyflate                 | 471 ms                                                 | 444 ms: 1.06x faster                                  |
| scimark_lu              | 120 ms                                                 | 114 ms: 1.06x faster                                  |
| fannkuch                | 410 ms                                                 | 392 ms: 1.05x faster                                  |
| dulwich_log             | 68.7 ms                                                | 65.8 ms: 1.04x faster                                 |
| 2to3                    | 274 ms                                                 | 264 ms: 1.04x faster                                  |
| scimark_sor             | 129 ms                                                 | 124 ms: 1.04x faster                                  |
| sqlite_synth            | 2.83 us                                                | 2.73 us: 1.04x faster                                 |
| xml_etree_parse         | 159 ms                                                 | 155 ms: 1.03x faster                                  |
| scimark_monte_carlo     | 74.6 ms                                                | 72.7 ms: 1.03x faster                                 |
| nqueens                 | 86.2 ms                                                | 84.0 ms: 1.03x faster                                 |
| mako                    | 11.5 ms                                                | 11.5 ms: 1.00x slower                                 |
| django_template         | 35.0 ms                                                | 35.2 ms: 1.01x slower                                 |
| sympy_integrate         | 21.2 ms                                                | 21.4 ms: 1.01x slower                                 |
| pickle_pure_python      | 326 us                                                 | 329 us: 1.01x slower                                  |
| pathlib                 | 18.9 ms                                                | 19.1 ms: 1.01x slower                                 |
| hexiom                  | 6.54 ms                                                | 6.63 ms: 1.01x slower                                 |
| sympy_sum               | 167 ms                                                 | 170 ms: 1.01x slower                                  |
| xml_etree_iterparse     | 106 ms                                                 | 107 ms: 1.02x slower                                  |
| regex_dna               | 209 ms                                                 | 212 ms: 1.02x slower                                  |
| chameleon               | 7.41 ms                                                | 7.55 ms: 1.02x slower                                 |
| sympy_str               | 296 ms                                                 | 302 ms: 1.02x slower                                  |
| unpickle_list           | 5.04 us                                                | 5.20 us: 1.03x slower                                 |
| nbody                   | 92.2 ms                                                | 95.1 ms: 1.03x slower                                 |
| pidigits                | 187 ms                                                 | 194 ms: 1.04x slower                                  |
| raytrace                | 308 ms                                                 | 320 ms: 1.04x slower                                  |
| go                      | 140 ms                                                 | 148 ms: 1.05x slower                                  |
| logging_silent          | 108 ns                                                 | 113 ns: 1.06x slower                                  |
| tornado_http            | 101 ms                                                 | 107 ms: 1.06x slower                                  |
| sympy_expand            | 476 ms                                                 | 506 ms: 1.06x slower                                  |
| chaos                   | 67.5 ms                                                | 72.7 ms: 1.08x slower                                 |
| regex_v8                | 22.7 ms                                                | 24.8 ms: 1.10x slower                                 |
| unpickle_pure_python    | 230 us                                                 | 254 us: 1.10x slower                                  |
| richards                | 46.0 ms                                                | 51.5 ms: 1.12x slower                                 |
| deltablue               | 3.71 ms                                                | 4.16 ms: 1.12x slower                                 |
| json_dumps              | 10.6 ms                                                | 12.4 ms: 1.17x slower                                 |
| Geometric mean          | (ref)                                                  | 1.03x faster                                          |

Benchmark hidden because not significant (2): pycparser, crypto_pyaes
Ignored benchmarks (40) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, async_generators, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_io, async_tree_io_tg, async_tree_memoization, async_tree_memoization_tg, async_tree_none, async_tree_none_tg, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, bench_mp_pool, bench_thread_pool, comprehensions, coroutines, coverage, create_gc_cycles, dask, deepcopy, deepcopy_memo, deepcopy_reduce, docutils, gc_traversal, generators, gunicorn, mdp, mypy2, pprint_pformat, pprint_safe_repr, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, sqlglot_normalize, sqlglot_optimize, sqlglot_parse, sqlglot_transpile, tomli_loads, typing_runtime_protocols
Ignored benchmarks (2) of results/bm-20220113-3.11.0a4-9471106/bm-20220113-linux-x86_64-python-main-3.11.0a4-9471106.json: html5lib, thrift


# HPT report

- Reliability score: 82.46% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
